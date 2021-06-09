# CSS Transforms, Transitions, and Animations


The transition-property CSS property sets the CSS properties to which a transition effect should be applied.



**Syntax**


``/* Keyword values */
transition-property: none;
transition-property: all;

/* <custom-ident> values */
transition-property: test_05;
transition-property: -specific;
transition-property: sliding-vertically;

/* Multiple values */
transition-property: test1, animation4;
transition-property: all, height, color;
transition-property: all, -moz-specific, sliding;

/* Global values */
transition-property: inherit;
transition-property: initial;
transition-property: unset;``



*fade transition*

1. Fade-in Image Transition
2. Fade-in Text Transition
3. Fade-in on Hover Animation
4. Fade-in on Scroll Animation
5. Fade Background Transition

``.fade
{
        opacity:0.5;
}
.fade:hover
{
        opacity:1;
}``



Change color Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them. Now, we just set the div’s class to “color” and specify the color we want in our CSS:

``.color:hover
{
        background:#53a7ea;
}``



That flex property above is what’s known as a shorthand CSS property. And really what this is doing is setting three separate CSS properties at the same time. So what we wrote above is the same as writing this:

``.child {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}``