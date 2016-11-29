# [HTML Class Notes](https://classroom.udacity.com/courses/cs253/lessons/48737165/concepts/487440410923)

### HTML skeleton
The skeleton HTML can be supplied through emmet with "!" + tab.

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Document</title>
    </head>
    <body>
        
    </body>
    </html>
In the head tag is the CSS and javascript that is contained in the
html code instead of separated into multiple documents.

### Bold Tag
The bold tag is `<b>text to bold</b>`. Like **this**.

### Italics Tag
The `<em>` tag makes text italic. Here is a *good example*.

### Hyperlinks
Hyperlinks are done with the `<a>` tag. A is for anchor. For example,
`<a href="www.google.com">This is your hyperlink text.</a>` will look like
[This is your hyperlink text.](www.google.com)

### Images
`<img src="url" alt="text">` The alt-text is displayed if the image cannot load. 

It is semi-required. Good for blind people.
This is a void tag. It has no content and requires *no* closing tag.

### Whitespace
A linebreak can be created with the `<br>` tag. The `<br>` tag 
works **_inline_** within the text.

A paragraph can be created with the `<p></p>` tag which also creates a box model around the contained text. This is a **_block_** element.

### Span and Div
The `<span>text</span>` element is an inline element so the text it
highlights will be inline with the surrounding text and no block 
will be created around it for CSS decoration.

The `<div>text</div>` tag is a block element which surrounds text to 
allow it to be decorated 

Span and div are used to surround text and apply CSS formatting to
it using the `class` and `id` attributes.

### URLs
URL stands for uniform resource locator. So we have `http://www.udacity.com/`
where:  
1.  `http` is the protocol. Also there is ftp, https, etc.  
2.  `www.udacity.com` which is the hostname  
3.  `/` is the path.  

#### Query Parameters or Get Parameters
Query parameters are added onto the end of a URL with a "?". For example:
http://example.com/foo?P=1
Here the query parameter is P=1. To add more query parameters, connect them with an ampersand.
http://example.com/foo?P=1&q=neat

#### Fragments
A fragment is separated from the URL by a hash sign "#". A fragment does not exist in the server. It is only client side.


#### Port
http:// localhost:8000/
Add the port after the host and before the path.

### HTTP Protocol
An HTTP request is composed of the GET request:
`GET /foo HTTP:/1.1`

The whole string is called the request line. Here `GET` is the method. `/foo` is the path and `HTTP/1.1` is the version.




















