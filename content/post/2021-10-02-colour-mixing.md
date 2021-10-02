+++
author = "Alex Nuttall"
date = 2021-10-02
title = "Connect Four"
+++
<iframe width="100%" height="500" name="iframe" src="https://goofy-bhaskara-6f277b.netlify.app/"></iframe>

[source code](https://github.com/thick-hollins/c4)

I wanted to have ago at programming a computer player, and I chose Connect Four for this purpose. Most of the computer's moves are random, it only knows how to score a winning move (horizontally, vertically or diagonally) when the opportunity exists, and how to (try to) block your potential winning moves. 

I would like to come back to this and add some analysis of sequences of two in terms of attacking and defending. I would like to give the computer some kind of default strategic behaviour. To make a good computer player, I'm sure you would need to analyse future steps, and not just the current game-state.