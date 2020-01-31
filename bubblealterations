var x;
var y;
var radius;

function setup() {
  createCanvas(400, 400);
  x = random(width);
  y = random(height);
  radius = 40;
}

function draw() {
  background(255);

  if (dist(mouseX, mouseY, x, y) < radius) {
    if (mouseIsPressed) {
      x = (mouseX);
      y = (mouseY);
    }
    fill(50, 0, 150, 75);
  }
  else {
    fill(15, 90, 60, 200);
  }

  ellipse(x, y, radius);
  x += random(-4, 4);
  y += random(-4, 4);
}
