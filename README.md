# Hellow-World
Hello World
void setup() {
  size(480, 480);
 fill(255, 255, 255);
  ellipse(300, 300, 80, 80); 
}

void draw() {
  
  
  fill(255, 0, 0);
  rect (20, 20, 50, 30);
  
  fill(0, 255, 0);
  rect (160, 20, 50, 30);
   
  fill(0,0, 255);
  rect (290, 20, 50, 30);
}
void mousePressed(){
  if(mouseX<70 && mouseX>20 && mouseY<50 && mouseY>20){
  fill(255, 0, 0);
  ellipse(300, 300, 80, 80);
  }
  if(mouseX<210 && mouseX>160 && mouseY<50 && mouseY>20){
      fill(0, 255, 0);
  ellipse(300, 300, 80, 80);

  }
   if(mouseX<340 && mouseX>290 && mouseY<50 && mouseY>20){
      fill(0, 0, 2255);
  ellipse(300, 300, 80, 80);
   }
}
