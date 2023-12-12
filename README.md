# cosas-p5

let ancho = 400;
let alto = 400;
let tamrect = 200;

function setup() {
    createCanvas(ancho, alto);
    background(176, 72, 181);

stroke (0, 255, 0);
strokeWeight(0);

fill(0, 0 ,255);
rect(ancho/2, alto/2, tamrect, tamrect);
  
fill(255, 0, 0);
rect(0, 0, tamrect, tamrect);
  
fill (0, 255, 0);
rect (ancho/2, alto/160, tamrect, tamrect);
  
fill (0, 0, 0)
  circle(width/2, height/2, 150);
  
stroke(0,0,0)
  strokeWeight(19)
  line(0, 0, width, height);
}
