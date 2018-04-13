# MCA - Material Community Animated

The project consists of designing a simple structure and animations of components and screen transitions, using a declarative form of css classes.

**Ex:**

`<div class="mc-animated anim-fade">`Hello World!`</div>`

Fade-in effect: _mc-animated anim-fade_\
Fade-out effect: _mc-animated anim-fade reverse_

# Let's go

To start we always use _the mc-animated_ class followed by some animation class as an example _anim-fade_.

##  Output effects 

For practically every class of animation you can use the use of the _reverse_ class so that the animation is reversed.

**Ex:**

_mc-animated anim-fade reverse_


## Basic animation speeds

By default most of the animations use the duration of 0.225s, but we can accelerate or decelerate the animations, using the classes _slow_ and _fast_, respectively. In addition, you can specify time duration with class _test_ to debug view animation.

_slow_ - 0.325 milleseconds\
_fast_ - 0.125 milleseconds\
_test_ - 4 seconds. Used for debug detail how the animation is executed

**Ex.:**

_mc-animated anim-fade slow_\
_mc-animated anim-fade reverse fast_

## Basic start delay of animations

_delay-slow_ - 0.325 milleseconds\
_delay-fast_ - 0.125 milleseconds\
_delay-test_ - 4 seconds. Used for debug detail how the animation is executed

**Ex.:**

_mc-animated anim-fade delay-slow_\
_mc-animated anim-fade delay-fast_

