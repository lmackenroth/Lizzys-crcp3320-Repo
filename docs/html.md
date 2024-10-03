# HTML

Represented by tags

## Web Browsers

* Url - client makes a request to server
* browser reads html and uses it to determine the contents and how it should be displayed
* Web standards:
  * W3C
  * WHATWG
* Check that tags are supported/ commonly supported by most browsers

# Code

* start tag, content, then end tag: "<p>this is and html paragraph using '< p > content < /p >' </p>"
* self closing tags 
  * < tagname/ >
  * < br/ >
* nested elements:

<p> hey
    <p> here's a nested element  </p>  
    yippee
</p>    
```


* Attributes:
  * Class
    * a class for element
  * ID:
    * unique ID for element
    * no 2 elements have the same ID
      * not enforced by anything
  * style
    * inline CSS style for an html element
* HTml elements:
  * html
  * head
  * body - most content goes here
  * title - what is displayed on the tab
  * h1-h6 - headers of different sizes
  * hr - makes a horizontal line
  * p - paragraph
  * b/ strong - makes text bold
  * i - italic
  * here's an example:

```
<!DOCTYPE html>
<html>

<head>
 
</head>
    <title> title in tab </title>  
    
<body>
<h1> heading 1 </h1>
    <h2> heading 2 </h2>
    <h3>  heading 3 </h3>

    horizontal line  
    <hr>

    <p> here's the paragraph, <b>  and this is bold </b> </p>
    <p><i>this is some italic text</i> </p>

</body>

</html>
```
[Check out what it'll look like](./htmlex.html)