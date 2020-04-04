## CSS browser compatibility issue

### Browsers 
Chrome, firefox, Safari, Edge, IE6,7,8,9... 360, qq, opera, maxthon...

### fix solutions

1. css initialization
```
*{
	margin: 0;
	padding: 0;
}
```
thrid-party initialization: Normalize.css 

2. browser private properties
```
-moz
-ms
-webkit
-o
```
autoprefixer(can i use)

3. CSS hack
* _ 

