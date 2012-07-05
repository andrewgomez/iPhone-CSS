#iphone.css
*My just-for-fun experiment in CSS gradients*

`iphone.css` is an almost-certainly useless CSS file that allows you to insert an CSS iPhone with only three DIVs. The iPhone can be either black or white and is fully scalable (oooooooh! aaaaaaah!).

Feel free to suggest improvements! This was mostly a project to help me learn about the new CSS3 gradient features. Currently only supports webkit browsers with any reliability.

##Usage
To use iphone.css in your website, simply include the stylesheet in your webpage's `<head>`, add the following code where you'd like to have the iPhone:

```
<div class="iphone black">
  <div></div>
  <div></div>
</div>
```

Or the following for a white iPhone:

```
<div class="iphone white">
  <div></div>
  <div></div>
</div>
```

You can change the size of the iPhone by editing the first attribute of the CSS file:

```
.iphone { 
  font-size: 2px; /* edit this to change the size of the iPhone */
...
```

*Note: this currently only supports webkit, so be sure to make the appropriate browser additions if necessary!

##License
Animate.css is licensed under the &#9786; license. (http://licence.visualidiot.com/)
