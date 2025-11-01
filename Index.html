<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>Imran's Site</title>
<style>
body{
  margin: 0;
  height: 100vh;
  background-color: grey;
  overflow: hidden; /* verhindert Scrollbars */
}

#apple {
  width: 50px;
  height: 50px;
  background-color: green;
  position: absolute;
}

#wurfel {
  width: 50px;
  height: 50px;
  background-color: lightblue;
  position: absolute;
  top: 200px;
  left: 200px;
}
</style>
</head>
<body>
<div id="wurfel"></div>
<div id="apple"></div>

<script>
const wurfel = document.getElementById("wurfel");
const apple = document.getElementById("apple");

let wurfelx = 200;
let wurfely = 200;
let speed = 5;
let dirY = 1;
let dirX = 0;

// store which keys are pressed
const keys = {};

function applePosReset() {
  const lavax = Math.random() * (window.innerWidth - 50);
  const lavay = Math.random() * (window.innerHeight - 50);
  apple.style.left = lavax + "px";
  apple.style.top = lavay + "px";
}
applePosReset();

document.addEventListener("keydown", (e) => {
  if (e.key === "w" && dirY === 0) { dirX = 0; dirY = -1; }
  if (e.key === "s" && dirY === 0) { dirX = 0; dirY = 1; }
  if (e.key === "a" && dirX === 0) { dirX = -1; dirY = 0; }
  if (e.key === "d" && dirX === 0) { dirX = 1; dirY = 0; }
});

function loop() {
  wurfelx += dirX * speed;
  wurfely += dirY * speed;

  // keep cube inside the screen
  wurfelx = Math.max(0, Math.min(window.innerWidth - 100, wurfelx));
  wurfely = Math.max(0, Math.min(window.innerHeight - 100, wurfely));

  // update cube position
  wurfel.style.left = wurfelx + "px";
  wurfel.style.top = wurfely + "px";

  const wurfelRect = wurfel.getBoundingClientRect();
  const appleRect = apple.getBoundingClientRect();

  if (checkCollision(wurfelRect, appleRect)) {
    applePosReset(); // move apple
  }

  // repeat forever
  requestAnimationFrame(loop);
}

function checkCollision(rect1, rect2) {
  return !(
    rect1.right < rect2.left ||
    rect1.left > rect2.right ||
    rect1.bottom < rect2.top ||
    rect1.top > rect2.bottom
  );
}
loop();
</script>
</body>
</html>
