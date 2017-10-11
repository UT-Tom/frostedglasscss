# Frosted Glass
or foggy glass, blurred div on a background, blah blah blah, etc.

### Technique 1: Photoshop
Take a regular background image

<p><img src="back.jpg" width="160px" height="90px;"></p>

<p>and blur it however you like in Gimp/Photoshop:</p>

<p><img src="back-.jpg" width="160px" height="90px;"></p>

<p>Save the original and blurred image.</p>

<p>Set the body's background to the original image<br/>
and the div's background to the blurred image.</p>

<h3>CSS</h3>

<pre>
body {
background: url('original_background.jpg') no-repeat;
background-size: cover;
background-position: center;
background-attachment: fixed;
}

.my_div {
background: url('blurred_background.jpg') no-repeat;
background-size: cover;
background-position: center;
background-attachment: fixed;

/* Set the width/height so you can check it out. */
width: 70%;
height: 200px;

margin: 12% auto;
}
</pre>

<p><small>magik.</small></p>

### Technique 2: ::before
