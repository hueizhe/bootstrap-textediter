## Bootstrap TextEditer


**Features:**

- Responsive and easy to implement.
- Styled with Bootstrap 3 and Font Awesome 4
- A word counter to count the number of words.

### Install


1. Include the jQuery library and other necessary resources in the Html document.
```sh
$ npm i -g gulp
```
<link href="http://netdna.bootstrapcdn.com/bootstrap/3.1.1/css/bootstrap.min.css" rel="stylesheet">

<link href="http://netdna.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css" rel="stylesheet">

<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>

<script src="http://netdna.bootstrapcdn.com/bootstrap/3.1.1/js/bootstrap.min.js"></script>

2. Include the jQuery LineControl Editor plugin's javascript and CSS after jQuery library.

<link href="editor.css" type="text/css" rel="stylesheet"/>
<script src="editor.js"></script>
3. Create an empty container element for the text editor.

<div id="txtEditor"></div> 
4. Call the plugin on the container element.

<script type="text/javascript">
$(document).ready( function() {
$("#txtEditor").Editor();                    
});
</script>

