# Fish-Tank
Everytime one restarts the program, a fish tank of jellyfish, underwater bugs, and octopuses relocate randomly and multiply in number randomly. 
Also please note that this html code was ran in khanacademy's compiler :)

background(23, 230, 202);
var octupus = function(x,y){
  var octupus = getImage("space/octopus");
  image(octupus,x,y);
};
var jellyfish = function(x,y){
  var jellyfish = getImage("avatars/marcimus");
  image(jellyfish, x, y);
};
var bug = function(x,y){
    // Draw the image at its default size
    var bug = getImage("cute/EnemyBug");
    image(bug, x, y);
 };
for (var i =0; i<random(4,15);i++){
    bug(random(0,200),random(0,300));
    jellyfish(random(0,200),random(0,300));
    octupus(random(0,200),random(0,300));
}

// draw a rectangle at (100, 50) with width 200 and height 100
//rect(0, 300, 300, 40);

