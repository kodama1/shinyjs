# [jQuery Shiny]()
#### Fast way to make elements fade onload.

Usage
-----

Just include [jquery.shiny.js] after jQuery. Requires jQuery 1.4+.

## HTML

``` html
<script src='jquery.js'></script>
<script src='jquery.shiny.js'></script>
```

## Javascript


### Basic

``` javascript
$('.foo').shiny();
```

To make the script run when the page load, you need to put the "shiny" inside a load or read function, like this:

``` javascript
$(document).ready(function(){
	$('.foo').shiny();
})
```
### If this plugin was usefull to you, please send me a tweet (@marcuscaum)! We are open to receive any ideas to make this plugin better every day. 