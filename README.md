C 18 PROJECT
BUGS
	After 200, the obstacles come in less amounts and the game becomes easy
	The screen size is not very large in length
	The clouds are covering the game over icon
	Lifetime of clouds is less as we can see them disappearing
crows are not appearing
high score is not implemented
screen doesn't become dark after every 800 metres
FIX
	World.framecount % (60-3*score/100) =0
	Create canvas (700,200)
	Cloud.depth=1; gameover.depth=2;
	Cloud.lifetime=210
a seperate function spawnCrows like we did for the obstacles
text(highscore, x, y)
if(World.framecount%800===0){
  background(0)
}
