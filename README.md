void setup() {
  size(600,600);
  background(255,255,255);
}

void draw() {
  background(255,255,255); // paints all the pixels this color
  fruit_bowl();
  table();
  chair();
}

void table() {
  // (legs) thin, brown rectangles
fill(80,40,10);
rect(420,250,20,200);
rect(60,250,20,200);
 // (top) brown, wide, flat rectangle with a black rectangle on top
rect(50,250,400,30);
fill(0);
rect(45,250,410,10);
}

void fruit_bowl() {
  // (fruit) colorful shapes 
fill(200,200,20);
circle(200,220,10);
fill(200,100,20);
circle(210,215,14);
fill(200,50,200);
circle(218,220,12);
fill(40,100,200);
circle(210,220,14);
fill(200,200,20);
circle(175,220,10);
fill(200,100,20);
circle(180,215,14);
fill(200,50,200);
circle(190,220,12);
fill(40,100,200);
circle(220,220,14);
  // (bowl) light brown half circle
  fill(120,80,50);
arc(200, 226, 100, 50, 0, PI, CHORD);

}
void chair() {
  // (seat) small, wide brown rectancle
 fill(120,80,50);
  rect(450,350,100,10);
  //(legs) slanted, thin triangles
triangle(450,350, 470,350, 420,450);
triangle(550,350, 530,350, 580,450);
  //(back) slated thin triangle
triangle(550,350, 530,350, 550,250);
 }

 
