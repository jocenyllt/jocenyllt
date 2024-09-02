
sketch.js
Salvo: 2 minutos atrás
1
function setup() {
2
  createCanvas(700, 700);
3
  background("black");
4
}
5
​
6
function draw() {
7
  
8
 stroke("yellow");
9
 fill("green");
10
  
11
  // console. log(mouseIsPressed);
12
  
13
  if(mouseIsPressed) {
14
     rect(mouseX, mouseY, 30, 40);
15
  } 
16
 }
