# CHAPTER 4
## Resetting CSS for new webpage | <img src="https://github.com/Ninja-Vikash/Assets/blob/main/Asset%20Icon/cssLogo.png" height="20px"> CSS Colors

### 🔵 Why do we need to reset our webpage before styling?
Before styling our webpage, we must reset CSS because every element has some space surrounding it by default.
<br>
**For resetting default CSS we will use universal selector`*`**
```
* {
  margin : 0;
  padding : 0;
  box-sizing : border-box;
}
```

### 🔵 Use of Colors in CSS <img src="https://github.com/Ninja-Vikash/Assets/blob/main/Asset%20Icon/cssLogo.png" height="20px">
We can set colors in CSS in multiple methods-
1. Using the name of color - `color : red`
2. Using RGB value - `color : rgb(0, 0, 0)`
3. Using HEX value - `color : #000`
4. Using HSL value - `color : hsl(40, 60%, 50%)`

### 🔵 What is RGB value? | What is RGBA value?
The rgb() function defines colors using the Red-green-blue (RGB) model.
<br>
An RGB color value is specified with `rgb(red, green, blue)`. Each parameter defines the intensity of that color and can be an integer between 0 and 255.
<br>
For example `rgb(255, 0, 0)` = red <br>
**Note**: We can set the opacity of color by adding one more letter in rgba(), where 'a' defines the alpha value i.e., the opacity of the color.
<br>
As `rgb(255, 0, 0, 0.5)` <br>
The alpha parameter uses a range between 0.0 (fully transparent) and 1.0 (Not transparent)
<pre>
.class {
  color : rgb(255, 0, 0, 0.7)
}
</pre>

### 🔵 What is HEX value?
A hexadecimal color is specified with: #RRGGBB, where the RR (red), GG (green) and BB (blue) hexadecimal integers specify the components of the color.
<br>
A HEX color value is specified with `#rrggbb`. Where rr defines red color, gg defines green color, bb defines blue color. Each parameter defines the intensity of that color as rgb color and can be a range between 00 and ff.
<br>
For example `#00ff00` = green <br>
**Note**: We can also set the opacity in HEX color using extra two hexadecimal values. <br>
As `#00ff000b`
<pre>
.class {
  color : #00ff000b;
}
</pre>

### 🔵 What is HSL value?
HSL stands for hue, saturation, and lightness. <br>
Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue. Saturation is a percentage value. 0% means a shade of gray, and 100% is the full color. Lightness is also a percentage. 0% is black, 50% is neither light or dark, 100% is white
<pre>
.class {
  color : hsl(40, 60%, 50%)
}
</pre>


> **Most Useful color values are HEX, RGB**

<br>
**WE USE ALL THESE COLOR VALUES IN ALL COLOR-RELATED PROPERTIES** <br>  _color_, _background-color_, _border-color_, and so on...
