# Transforms

transforms came with two type:

1-two-dimensional.

2-three-dimensional.


Transform Syntax:

example

transform: scale(1.5);

#  2D Transforms:

Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes.



Transform elements :

2D Rotate accept value from 0-360 positive or negative.

example

transform : rotate(20deg);

2d Scale

tarnsform: scale(.75) or scalex or scale y or scale(.86,2);


2D translate

transform : translate(-10px, 25%);

2D skew

transform : skew(5deg, -20deg);

transform : perspective(200px) rotateX(45deg);


3D scale:
 transform : perspective(200px) rotateX(45deg);


3D translate: 

 transform: perspective(200px) translateZ(-50px);


# Transition

example

 background: #2db34a;

  transition-property: background;

  transition-duration: 1s;

  transition-timing-function: linear;


.box:hover {

  background: #ff7b29;

}



we can use in duration 

transition-duration: .2s, 1s;

timing function:

example

  transition-timing-function: linear, ease-in;

delay befor start action.

transition-delay: 0s, 1s;


shorthand transition:

  transition: background .2s linear, border-radius 1s ease-in 1s;

8 simple css :

1- Fade in:

.fade
{
        opacity:0.5;
}
.fade:hover
{
        opacity:1;
}


2- change color


.color:hover
{

        background:#53a7ea;

}


3- Grow and Shrink


.grow{

transform :scale(2);

}


shrink{

transform :scale(.5);

}

4-rotate element

rotatez(-30px);

5- Square to circle:

border-redius:50%;

6-shadow

box-shadow:
  1px 1px #53a7ea,

  2px 2px #53a7ea,

  3px 3px #53a7ea;

 -webkit-transform: translateX(-3px);

  transform: translateX(-3px);

}

7- swing

8- Inset border

box-shadow: inset 0 0 0 25px #53a7ea;




























