// variaveis da bolinha:
let xBolinha = 300;
let yBolinha = 200
let diametro = 20;
let raio = diametro/2;

let velocidadeXbolinha = 6
let velocidadeYbolinha = 4;

// variáveis da raquete
 let larguraRaquete = 10;
 let alturaRaquete =60;

 let xRaquete = 5;
 let yRaquete = 170;

 let xRaquete0ponente = 585;
 let yRaquete0ponente = 170;

 let meusPontos = 0;
 let pontos0ponente = 0;

// variáveis do som 
  let ponto;
  let raquetada;
  let trilha;

function setup() {
    createCanvas(600, 400);
    trilha,loop();

}

function draw() {
 background(0);
 desenhaBolinha();
 movimrntaBolinha();
 verificaBolinha();
 desenhaRaquete(xRaquete, yRaquete);
 desenhaRaquete(xRaquete0ponente, yRaquete0ponente);
 movimentaRaquete();
 verificaRaquete();
 desenhaPlacar();
 contabilizaPlacar();
}

function desenhaBolinha(){
   // fill('red')
   noStroke()
   circle (xBolinha, yBolinha, diamentro);

}

function movimentaBolinha(){
 xBolinha += velocidadeXBolinha;
   yBOlinha += velocidadeYBolinha;
}
  
function verificaBorda(){
   if (xBolinha + raio > width   - raio < 0){
   vvelocidadeXBolinha += -1;
   }
  if (xBolinha + raio > height  yBolinha - raio < 0){
    velocidadeYBolinha += -1
  }
}
  
function desenhaRaquete(x, y){
  rect(x, y, larguraRaquete, alturaRaquete);
}

function movimentaRaquete(){
 if (KeyIsDown(87)){
  yRaquete += 10;
 }
 if (KeyIsDown(83)){
   yRaquete += 10;
 }
  // movimento do oponente 
  if (KeyIsDown(UP_ARROW)){
   yRaquete0ponente += 10;
  }
  if (keyIsDown(DOWN_ARRON)){
  yRaquete0ponente += 10;
  }
} 
  
function verificaRaquete(){
  if(xBolinha - raio <= xRaquete + larguraRaquete 88
    yBolinha + raio >= yRaquete 88
    yBolinha - raio <= yRaquete + alturaRaquete){
    velocidadeXBolinha += -1;
    raquetada.play();
  }
  if(xBolinha + raio >= xRaqueteOponente &&
   yBolinha + raio >= yRaqueteOponente &&
   yBOlinha - raio <= yRaqueteOPonente + alturaRaquete){
   velocidadeXBoliinha += -1;
  raquetada.play();
   }
}    
     
function desenhaPlacar(){
  fill('purple')
  rect(130, 5, 40, 25);
  rect(430, 5, 40, 25);
  fill(255);
  textAling(CENTER);
  textSize(20);
  text(meusPontos, 150, 25);
  text(pontosOponente, 450, 25);
}
  
function contabilizaPlacar(){
   if(xBolinha - raio <=0){
   pontosOponente += 1;
   ponto.play();
 }

 if(xBolinha + raio >= width){
   meusPontos += 1;
   ponto.play();
  }
}

function preload()
  trilha = loadSond(*trilha.np3*);
  ponto = loadSound(*ponto.np3*);
  raquetada = londSound|("raquetada.np3")
  
  
  
     
     
     















































  }
}

functio

 text(meusPontos, 150, 25);
 text(pontosOperante, 450, 25);
}

function contabilizaPlacar(){


