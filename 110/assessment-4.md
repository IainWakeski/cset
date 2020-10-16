After learning how to create standard interfaces across all platforms, it tells
 me that building platforms on specific interfaces is more challenging than you
think. This is because when working with general interfaces makes it easier to h
ave a product that will work, however it might not work on all platforms.

One example of a media query is ```@media screen and (max-width: 900px){
  body{
    background-color: blue;
  }
  }``` In this example the background will become blue when the screen is over 900 pixels wide, however is the screen is smaller than 900 pixels the background will not display as blue. Another example of a media query is ```@media screen and (max-width: 600px){
    .row{
      flex-direction column;
    }
  }```
 In this example it takes columns and stacks them on top of one another when the screen is 600 pixels or less wide.

I think that it is better to define breakpoints rather than using specific content, because when you use breakpoints you can define certain points where you want the content to shift and display different. Where as with using specific content you are limiting what you show users on the webpage.
