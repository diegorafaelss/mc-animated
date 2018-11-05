# MCA - Material Community Animated

The project consists of designing a simple structure and animations of components and screen transitions, using a declarative form of css class.

**Ex.:**

`<div class="mc-animated anim-fade-in">`Hello World!`</div>`

Fade-in effect: _mc-animated anim-fade-in_\
Fade-out effect: _mc-animated anim-fade reverse_

# Let's go

To start we always use _the mc-animated_ class followed by some animation class as an example _anim-fade_.

##  Output effects 

For practically every class of animation you can use the use of the _reverse_ class so that the animation is reversed.

**Ex.:**

_mc-animated anim-fade-in reverse_


## Basic animation speeds

By default most of the animations use the duration of 0.225s, but we can accelerate or decelerate the animations, using the classes _slow_ and _fast_, respectively. In addition, you can specify time duration with class _test_ to debug view animation.

_slow_ - 0.325 milleseconds\
_fast_ - 0.125 milleseconds\
_test_ - 4 seconds. Used for debug detail how the animation is executed

**Ex.:**

_mc-animated anim-fade-in slow_\
_mc-animated anim-fade-in reverse fast_

## Basic start delay of animations

Default speed: 0.225 milleseconds\

_delay-slow_ - 0.325 milleseconds\
_delay-fast_ - 0.125 milleseconds\
_delay-test_ - 4 seconds. Used for debug detail how the animation is executed

**Ex.:**

_mc-animated anim-fade-in delay-slow_\
_mc-animated anim-fade-in delay-fast_



## Basic list animations

**Pack Fade basic**

anim-fade-in\
anim-fade-out

**Pack Shake**

anim-shake

**Pack Slide Fade 3D**

anim-slide-fade-3d-left\
anim-slide-fade-3d-right\
anim-slide-fade-3d-top\
anim-slide-fade-3d-bottom

**Pack Slide Fade**

anim-slide-fade-left\
anim-slide-fade-right\
anim-slide-fade-top\
anim-slide-fade-bottom

**Pack Slide Short**

anim-slide-short-left\
anim-slide-short-right\
anim-slide-short-top\
anim-slide-short-bottom

**Pack Slide**

anim-slide-left\
anim-slide-right\
anim-slide-top\
anim-slide-bottom

**Pack Zoom Elastic**

anim-zoom-elastic-in\
anim-zoom-elastic-Out

**Pack Zoom Fade**

anim-zoom-fade-in\
anim-zoom-fade-out

**Pack Zoom basic**

anim-zoom-in\
anim-zoom-Out
