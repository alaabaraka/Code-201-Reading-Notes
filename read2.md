When you’re working with HTML, styles, and scripts and you’re working on a big project, I really recommend separating files in different folders. Have all of your CSS files in one folder and all your JavaScript files in another folder. Do the same for your HTML files.

To link a CSS file with your HTML file, you have to write the next script on your HTML file inside the head tag.

<link rel=¨stylesheet¨ type=¨text/css¨ href=¨..\[folder_name]\[file_name].css¨>

If you have the CSS file in the same folder as your HTML file, you only have to write the name of your CSS file, like this (I recommend having the files in different folders associated by the type):

<link rel=¨stylesheet¨ type=¨text/css¨ href=¨[file_name].css¨>

If you’re working with a bootstrap theme, you can add the link of the file:

<link rel=¨stylesheet¨ type=¨text/css¨ href=¨[url_bootstrap_theme]¨>

To link a Js file with your HTML, you only have to add the source of the script inside the body tag or outside; it doesn’t matter.

<script src="..\[folder_name]\[file_name].js"></script>

If you have the Js file in the same folder as your HTML file you only have to write the name of your Js file, like this (I recommend having the files in different folders associated by the type):

<script src="[file_name].js"></script>

If you are working with libraries, like jQuery (Links to an external site.), you can add the URL of the library in the source.

<script src="[url_of_the_js_library]"></script>
