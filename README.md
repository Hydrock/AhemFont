# AhemFont
Test Font

<img src="https://raw.githubusercontent.com/Hydrock/AhemFont/master/img/ahem-preview.jpg" width="100%" height="auto" alt="ahem fonr preview">

https://www.w3.org/Style/CSS/Test/Fonts/Ahem/ - original file and description

http://www.hixie.ch/tests/evil/mixed/lineheight3.html - line-height tests with Ahem font

https://hydrock.github.io/AhemFont/ - Test page

You can connect a font by simply using this CSS

```CSS
@font-face {
  font-family: Ahem;
  src: url('https://raw.githubusercontent.com/Hydrock/AhemFont/master/font/ahem.eot'); /* IE9 Compat Modes */
  src: url('https://raw.githubusercontent.com/Hydrock/AhemFont/master/font/ahem.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('https://raw.githubusercontent.com/Hydrock/AhemFont/master/font/ahem.woff2') format('woff2'), /* Super Modern Browsers */
       url('https://raw.githubusercontent.com/Hydrock/AhemFont/master/font/ahem.woff') format('woff'), /* Pretty Modern Browsers */
       url('https://raw.githubusercontent.com/Hydrock/AhemFont/master/font/ahem.ttf')  format('truetype'), /* Safari, Android, iOS */
       url('https://raw.githubusercontent.com/Hydrock/AhemFont/master/font/ahem.svg#svgAhem') format('svg'); /* Legacy iOS */
}
.root {
  font-family: Ahem, sans-serif;
}
```
