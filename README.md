void setup(){
  size(500,500);
  background(255);
  stroke(0);
}
void draw(){
  fill(0);
  rect(0,30,15,490);
  rect(0,30,300,20);
  rect(0,480,200,400);
  line(300,50,300,100); // Corda 
  fill(209);
  ellipse(300,115,80,75); //Cap
  rect(270,152,60,140); //Cos
  ellipse(280,105,15,15); //Cercle ull esquerre
  ellipse(320,105,15,15); //Cercle ull dreta
  line(270,152,200,250); //Braç esquerre
  line(331,152,400,250); //Braç dreta
  line(270,293,250,400); //Peu esquerre
  line(330,291,350,400); //Per dreta
  point(280,104); //Punt del ull esquerre
  point(319,104); //Punt del ull dreta
  ellipse(300,120,10,8);//nas
  point(298,120); //nas
  point(302,120);//nas

}
