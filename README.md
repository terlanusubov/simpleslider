# AlzheimerSlider
## CREATE YOUR OWN SLIDER 

### Probably,you fad up to use owl carousel every time that you dont need.You need very simple slider.You need something easy.So this plugin is absolutely for you

## IN HTML
You can use class name that whatever you want.Do not use my reserved class names (reserved class names at the end)

```html
<div class="slider">
  <div class="content">
    <div class="slider1">Your Content</div>
    <div class="slider2">Your Content</div>    
    <div class="slider3">Your Content</div>    
    <div class="slider4">Your Content</div>    
  </div>
</div>
```


You have to link my css and js

{::nomarkdown}

<link rel="stylesheet"  src="alzheimer_slider.css">
<script src="js/alzheimer_slider.js"></script>

{:/}



AND LAST CALL FUNCTION



{::nomarkdown}
<script>
  Slider(".slider");
 </script>

{:/}

 
 
 
 ### You can make Loop,you can change next and prev icon,you can create circles,you can give loop speed

{::nomarkdown}
 Slider(".slider",{
 next:"fas fa-chevron-right",
 prev:"fas fa-chevron-left",
 loop:true,
 speed:2000
 })
{:/}
 
 
 MY RESERVED CLASS NAMES
 
 slider-main-wrapper
 slide-item
 slider-buttons
 slider-button-wrapper
 right-icon
 left-icon
 content
 
 
 
 THANKS FOR READING AT LEAST :)
