# AlzheimerSlider
## CREATE YOUR OWN SLIDER 

### Probably,you fad up to use owl carousel every time that you dont need.You need very simple slider.You need something easy.So this plugin is absolutely for you

## USING
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

```html

<link rel="stylesheet"  src="alzheimer_slider.css">
<script src="js/alzheimer_slider.js"></script>

```



AND LAST CALL FUNCTION



```html
<script>
  Slider(".slider");
 </script>

```

 
 
 
 You can make Loop
 You can change next and prev icon
 You can create circles
 You can give loop speed

```html
 Slider(".slider",{
 next:"fas fa-chevron-right",
 prev:"fas fa-chevron-left",
 loop:true,
 speed:2000
 })
```
 
 
### MY RESERVED CLASS NAMES
 
 <ul>
  <li>slider-main-wrapper</li>
  <li>slide-item</li>
  <li>slider-buttons</li>
  <li>slider-button-wrapper</li>
  <li>right-icon</li>
  <li>left-icon</li>
  <li>content</li>
</ul>
 
 
 
 ## THANKS FOR READING AT LEAST :)
