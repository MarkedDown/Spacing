
# Spacers

*Limiting the horizontal content area.*

<br>

## Preview

*This is how a lorem ipsum paragraph looks*  
*like with a spacing of `200px` on either side.*

<br>
<br>

[<img height = 220 width = 20% align = left  src = '../Resources/Space.svg' >][#]
[<img height = 220 width = 20% align = right src = '../Resources/Space.svg' >][#]

<div align = left>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Molestie nunc non blandit massa enim nec dui. Vitae congue mauris rhoncus aenean vel. Magna eget est lorem ipsum dolor. Eget magna fermentum iaculis eu. A erat nam at lectus urna duis convallis convallis. Fames ac turpis egestas integer eget. Tellus pellentesque eu tincidunt tortor aliquam. Risus sed vulputate odio ut. Urna et pharetra pharetra massa massa ultricies mi quis hendrerit. Eget est lorem ipsum dolor sit. Consequat ac felis donec et odio pellentesque diam. Tellus in metus vulputate eu scelerisque felis.

</div>

<br>
<br>

<div align = center>

> **Note** This is not the same as 'justify' for text alignment, it only limits the area.

</div>
	
<br>
<br>

## Markdown

*The markdown used to generate this.*

<br>

### Template

```html
[<img height = 220 width = 20% align = left  src = '../Resources/Space.svg' >][#]
[<img height = 220 width = 20% align = right src = '../Resources/Space.svg' >][#]
<div align = left>

<!-- Content Area, don't remove the above and below  -->
<!-- spaces / newlines if you want markdown to work. -->

</div>

[#]: #  <!-- Prevents Redirecting -->
```

<br>

### Space.svg

```svg
<svg width = '1' height = '1' version = '1.1' viewBox = '0 0 1 1' xmlns = 'http://www.w3.org/2000/svg'></svg>
```

<br>
<br>

## Details

An empty svg image is placed on either of  
the content area which limits said area.

Note that special pages like a repositories  
README have different inherent page widths.

You will have to find you own height by, for  
example using the DevTools ( **F12** ) or just  
guessing and checking the preview.

<br>

<!----------------------------------------------------------------------------->


[#]: #
