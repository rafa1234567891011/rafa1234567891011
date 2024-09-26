// a viagem de chihiro
// guardiões da galáxia
// as aventuras de pi
// paddington
// ladrões de bicicleta

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
}
// a viagem de chihiro, LIVRE
// guardiões da galáxia, 12
// as aventuras de pi, 10
// paddington, LIVRE
// ladrões de bicicleta, 12
// fantasia, aventura, drama

// a viagem de chihiro, LIVRE, fantasia, aventura
// paddington, LIVRE, fantasia, aventura
// as aventuras de pi, 10, drama, fantasia, aventura
// depois da chuva, 10, drama
// guardiões da galáxia, 12, fantasia, aventura
// ladrões de bicicleta, 12, drama
// o menino que descobriu o vento, 14, drama
idade >= 10
idade >= 14
let n = 1;
function draw() {
  background(220);
  if (n >=9){
    print(n);
  } else{
    print(n);
    n = n+2;
  }
}
function draw() {
    background(220);
    let recomendacao = "A viagem de Chihiro";
    text(recomendacao, width/2, height/2);
}
function draw() {
    background(220);
    let recomendacao = geraRecomendacao();
    text(recomendacao, width/2, height/2);
}

function geraRecomendacao() {
  return "A viagem de Chihiro";
}
function draw() {
    background(220);
    let recomendacao = geraRecomendacao();
    text(recomendacao, width/2, height/2);
}

function geraRecomendacao() {
  return "A viagem de Chihiro";
}
let campoIdade;

function setup() {
    createCanvas(400, 400);
    campoIdade = createInput("15");
}
function draw() {
    background(220);
    let idade = campoIdade.value();
    let recomendacao = geraRecomendacao(idade);
    text(recomendacao, width/2, height/2);
}
function geraRecomendacao(idade) {
    if (idade >= 10) {
        if (idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            return "As aventuras de Pi";
        }
    } else {
        return "A viagem de Chihiro";
    }
}
let campoIdade;

function setup() {
  createCanvas(400, 400);
  campoIdade = createInput("15");
}

function draw() {
  background(220);
  let idade = 15; // exemplo de idade
  let recomendacao = geraRecomendacao(idade);
  text(recomendacao, width / 2, height / 2);
}

function geraRecomendacao(idade) {
  if (idade >= 10) {
    if (idade >= 14) {
      return "O menino que descobriu o vento";
    } else {
      return "As aventuras de Pi";
    }
  } else {
    return "A viagem de Chihiro";
  }
}
function verificarNumeroDaSorte(______) {
_____(numero === 2 || numero === 11 || numero === 25) {
      ______"Você tirou o número da sorte!";
} _______ {
     return "Não foi dessa vez, tente novamente!";
       }
}
let variavelGlobal = "Eu sou global";

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
  text(variavelGlobal, 10, 30);
  exemploLocal();
}

function exemploLocal() {
  let variavelLocal = "Eu sou local";
  text(variavelLocal, 10, 50);
}
let variavelGlobal = "Eu sou global";

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
  text(variavelGlobal, 10, 30);
  exemploLocal();
}

function exemploLocal() {
  let variavelLocal = "Eu sou local";
  text(variavelLocal, 10, 50);
}
function draw() {
  background(220);
  text(variavelGlobal, 10, 30);
  text(variavelLocal, 10, 50);
function geraRecomendacao(idade, gostaDeFantasia) {
    if(idade >= 10) {
        if(idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if(gostaDeFantasia){
                return "As aventuras de Pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        return "A viagem de Chihiro";
    }
}
}
function draw() {
    background (220);
    let idade = campoIdade.value();
    let gostaDeFantasia = true;
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);
    text(recomendacao, width/2, height/2);
}
let campoIdade;
let campoFantasia;

function setup() {
    createCanvas(400, 400);
    campoIdade = createInput("15");
    campoFantasia = createCheckbox("Gosta de Fantasia ?");
}
function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);
    text(recomendacao, width / 2, height / 2);
}
function geraRecomendacao(idade, gostaDeFantasia) {
    if(idade >= 10) {
        if(idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if(gostaDeFantasia){
                return "As aventuras de Pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if(gostaDeFantasia) {
            return "A viagem de Chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}
function avaliarDesempenho(pontuacao, ______) {
    if (nivel === 'iniciante') {
        if (pontuacao >= 50) {
            return "Parabéns! Você passou para o próximo nível.";
        } else {
            return "Infelizmente, você não atingiu a pontuação necessária.";
        }
    } else if ___________ {
        if (pontuacao_____) {
            return "Bom trabalho! Você está se saindo bem.";
        } else {
            return ________________;
        }
    }
}
function geraRecomendacao(idade, gostaDeFantasia) {
    if (idade >= 10) {
        if (idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if (gostaDeFantasia) {
                return "As aventuras de pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if (gostaDeFantasia) {
            return "A viagem de chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}
function setup() {
    createCanvas(800, 400);
    campoIdade = createInput("5");
    campoFantasia = createCheckbox("Gosta de fantasia?");
}

function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}
function draw() {
    background(220);
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    fill(color(76, 0, 115)); // Um tom de roxo escuro
    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}
function draw() {
    background("white");
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    fill(color(76, 0, 115));
    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}
function setup() {
    createCanvas(800, 400);
    createSpan("Sua idade:");
    campoIdade = createInput("5");
    campoFantasia = createCheckbox(" Gosta de fantasia?");
}
function setup() {
    createCanvas(800, 400);
    createSpan("Sua idade:");
    campoIdade = createInput("5");
    campoFantasia = createCheckbox(" Gosta de fantasia?");
}

function draw() {
    background("white");
    let idade = campoIdade.value();
    let gostaDeFantasia = campoFantasia.checked();
    let recomendacao = geraRecomendacao(idade, gostaDeFantasia);

    fill(color(76, 0, 115));
    textAlign(CENTER, CENTER);
    textSize(38);
    text(recomendacao, width / 2, height / 2);
}

function geraRecomendacao(idade, gostaDeFantasia) {
    if (idade >= 10) {
        if (idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if (gostaDeFantasia) {
                return "As aventuras de pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if (gostaDeFantasia) {
            return "A viagem de chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}
html, body {
  margin: 30px;
  padding: 0;
}

canvas {
  display: block;
}
html, body {
  margin: 30px;
  padding: 0;
  background-color: rgb(221,233,251);
}

canvas {
  display: block;
}
function setup() {
  createCanvas(800, 400);
  createElement("h2", "Recomendador de filmes");
  createSpan("Sua idade:");
  campoIdade = createInput("5");
  campoFantasia = createCheckbox("Gosta de fantasia?");
}
function geraRecomendacao(idade, gostaDeFantasia) {
    if (idade >= 10) {
        if (idade >= 14) {
            return "O menino que descobriu o vento";
        } else {
            if (gostaDeFantasia) {
                return "As aventuras de pi";
            } else {
                return "Depois da chuva";
            }
        }
    } else {
        if (gostaDeFantasia) {
            return "A viagem de chihiro";
        } else {
            return "O feitiço do tempo";
        }
    }
}
