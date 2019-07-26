<h1>Shy Header</h1>
<p>A simple, light-weight and easy-to-use jQuery Plugin that shows/hides the header of the page when users scroll the page down more than its height. However, the header remains watching the page so when users scroll the page up its being showed.</p>
<p><a href="https://www.mamutlove.com/projects/shyheader/" title="Demo" target="_blank">Demo</a></p>
<p>Please, take this <a href="https://www.mamutlove.com/projects/shyheader/" title="Demo" target="_blank">demo</a> as it is, a little demo where I pretend to show the power of this plugin, but consider your own target before copy/paste the code. It is possible that you need to reset some properties contained in the CSS file.</p>

<h2>Customizable</h2>
<p>• You could change the name of the class that is going to be added to the header ('is-watching' by default). Remember then to apply your styles to this new class.</p>
<p>• Add an offset to your main container.<br>Due to the header is fixed to the top of the window, its height do not computable for the DOM, so the next sibling starts at the very top of the document. If you need to add an offset to this sibling equal as the header's height, set a class name 'shy-container' by default when initializing the plugin as a value for the option 'container'.</p>
<p>• Customize or change the CSS files.</p>

<h2>Usage</h2>
<p>• Download or fork the repository.</p>
<p>• Include jQuery and the Javascript file minify or not in your HTML.</p>
<pre>
    <b>// Initialize the plugin</b>
    $("your-header-selector").shyheader();
    <br>
    <b>// some options are available</b>
    $("your-header-selector").shyheader({
        classname : "is-watching",
        container : 'shy-container'
    });
</pre>

<h2>Credits</h2>
<p>• Feel free to download, modify, break, use or destroy this plugin.</p>"# shyheader" 
