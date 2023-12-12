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

### Standard Breakpoints - Mesia Queries .
 The size on the media query above as an a arbitrary value  had i just picked, but this is of course up to the developer to choose. There exists sort of standard values in the IT Business, I say sort of because there are many variants.But the standard values are as follows in chrome:
 -** 4 K** screen larger than 2560px
 -**Laptop L**: larger than 1440px
 -**Laptop **: larger than 1024px
 -** Tablet**: larger than 768px
 -**MobiLe L** larger than 425px
 -**Mobile M** larger than 375px
 -**Mobile S** larger than 320px