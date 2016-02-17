# media-piramide
void setup(){
size(500, 500);

}

void draw(){
int i=1;
int j=1;
for(i=1; i<=5; i++){
  for(j=1; j<=i;j++){
  ellipse(j*70, i*70, 50, 50);
}
}
}
