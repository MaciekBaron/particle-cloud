Particle Cloud
==============

This is a "semi-orbital" particle cloud animation that I've created around three years ago (2010) but have now 
updated and optimized to use `requestAnimationFrame` etc.. It's a Canvas based animation that uses I wrote from 
scratch without using any libraries (except jQuery, but it can be easilly rewritten to not require it).

The particles are randomly generated during the initialization stage (colour, size etc.) and then are non-randomly 
animated using quasi-physics that actually aren't similar to anything in real life.

Quasi-physics
-------------

The idea behind the "physics" over here is creating a "magnetic well" that attracts particles, and then repels them 
once they reach the "well". The particles accelerate until they reach their maximum velocity or until they reach the 
well. After reaching the well, they start deaccelerating based on the value of detraction set in the script. The 
particles do not travel to the well using a straight line - their path is actually curved in order to achieve a more 
interesting effect.

The smaller particles travel slower which creates an illusion of 3D.

Demo
----
By deafult the particles will follow your cursor (or finger on touch-screen devices). You can click to repel 
the particles.

[Demo with 200 particles](http://htmlpreview.github.com/?http://github.com/MaciekBaron/particle-cloud/blob/master/index.html)

[Demo with 500 particles](http://htmlpreview.github.com/?http://github.com/MaciekBaron/particle-cloud/blob/master/index.html?500)

[Demo with 1000 particles](http://htmlpreview.github.com/?http://github.com/MaciekBaron/particle-cloud/blob/master/index.html?1000)

[Demo with 2000 particles](http://htmlpreview.github.com/?http://github.com/MaciekBaron/particle-cloud/blob/master/index.html?2000)

[Demo with 10000 particles](http://htmlpreview.github.com/?http://github.com/MaciekBaron/particle-cloud/blob/master/index.html?10000) 
(warning, can be really slow!)
