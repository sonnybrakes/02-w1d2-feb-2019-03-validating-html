# Check your understanding - 03 - Validating HTML

## 1. What does title do?
> The HTML <title> element is used for declaring the title, or name, of the HTML document. The title is usually displayed in the browser's title bar (at the top). It is also displayed in browser bookmarks and search results. The title is placed inside the <title> tags </title> is nested inside the \<head> tags \</head> tags.
## 2. What information do images need, and why?
> The HTML \<img> tag is used for embedding images into an HTML document. The value given by the src attribute is the URL to the embedded image. The value of the alt attribute appears if the image cannot be loaded.
## 3. What's the difference between head and body?
> The HTML \<head> element represents a collection of metadata about the document, including links to or definitions of scripts and style sheets. There is only one set of \<head> tags \</head> nested inside of the \<html> tags \</html> in a document.

> The HTML \<body> element represents the content of an HTML document. There is only one set of \<body> tags \</body> nested inside of the \<html> tags \</html> element in a document.

> What's inside the \<head> tags \</head> is not seen by the user, what's inside is used to include relevant information and dynamic content that is processed by the browser.

## 4. Based on the messages from the validator, write the bare-minimum HTML you need to have a "valid" web page.
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <title>element must not be empty</title>
      </head>
      <body>
      document
      </  body>
    </html>
