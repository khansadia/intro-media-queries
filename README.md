# Intro Media Queries

### What is media queries ?

Media queries in CSS are way to apply styles to a web page based on the size of given screen. we can have rather large screen, and we can also have a very small one, like a mobile phone. This is very useful for creating responsive web page designs that adapt to different screen and devices .

How to we do this ?  Ofcourse by using media quries.
```css 
@media screen and (max-width:600px){
    /* Styles for screen with a maximun width of 600px */
    nav{
        background-color: red ;
    }
}
```
-'@media': this is keyword that indicates the begning of a media query.
-'screen': specifies that the style within the media query should only apply to devices with screens.(not devices that might not have screen, like printers)
-'(max-width:600px)': this is the condition that must be true in order for the styles within the media query to be applied. In this case, the styles will only apply if yhe screen width is 600px or less.

There are many more ways you can specify your condition, but in the majority of cases we use 'max-width' or something that is

