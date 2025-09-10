# Three-Shapes
shapes for homework

# Shape 1 
void setup() {
  size(600,600);
  background(255,255,255);
}

void draw() {
  background(255,255,255); // paints all the pixels this color
  table();
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
