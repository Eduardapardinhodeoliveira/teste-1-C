# teste-1-C
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
}function setup() {
  createCanvas(400, 400);
}
…  background(220);
  fill("black");
  let palavra = "Caminhante";
}
function draw() {
  background(220);
  fill("black");
  let palavra = "Caminhante";
  text(palavra, 200, 200);
}
function draw() {
  background(220);
  fill("black");
  let palavra = "Caminhante";
  textAlign(CENTER, CENTER);
  text(palavra, 200, 200);
}
function draw() {
  background(220);
  fill("black");
  let palavra = "Caminhante";
  textSize(64);
  textAlign(CENTER, CENTER);
  text(palavra, 200, 200);
}
function draw() {
  background(220);
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER);
  
  let palavra = "Caminhante";
  text(palavra, 200, 200);
}
function draw() {
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER);
  
  let palavra = "Caminhante";
  text(palavra, 200, 200);
}
function draw() {
    background("white");
    fill("black");
    textSize(64);
    textAlign(CENTER, CENTER);
  
    let palavra = "Caminhante";
    text(palavra, 200, 200);
    
    if(mouseX < 50) {

    } 
}
function draw() {
    background("white");
    fill("black");
    textSize(64);
    textAlign(CENTER, CENTER);
  
    if(mouseX < 50) {
        let palavra = "C";
        text(palavra, 200, 200);
    } 
}
if(mouseX < 50) {
    let palavra = "C";
    text(palavra, 200, 200);
} else {
    let palavra = "Caminhante";
    text(palavra, 200, 200);
}
map(mouseX, 0, width, 0, palavras.length)
function draw() {
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER)
  
//  if(mouseX < 50){
//    let palavra = "C";
//    text(palavra, 200, 200);
//  } else {
//    let palavra = "Caminhante";
//    text(palavra, 200, 200);
//  }
}
let quantidade = map(mouseX, 0, width, 1, palavra.length);
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER)
  
  let maximo = width;
  let minimo = 0;
  let palavra = "Caminhante";
  let quantidade = map(mouseX, 0, width, 1, palavra.length);
  let parcial = palavra.substring(0,quantidade);
  text(parcial,200,200);
  
//  if(mouseX < 50){
//    let palavra = "C";
//    text(palavra, 200, 200);
//  } else {
//    let palavra = "Caminhante";
//    text(palavra, 200, 200);
//  }
}
