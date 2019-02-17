# Check your understanding - 03 - Validating HTML
    1. What does title do?
    The HTML <title> tag is used for declaring the title, or name, of the HTML document. The title is usually displayed in the browser's title bar (at the top). It is also displayed in browser bookmarks and search results. The title tag is placed between the opening and closing <head> tags.

    2. What information do images need, and why?
    The HTML <img> tag is used for embedding images into an HTML document. The value given by the src attribute is the URL to the embedded image. The value of the alt attribute appears if the image cannot be loaded.

    3. What's the difference between head and body?
    - The HTML <head> element represents a collection of metadata about the document, including links to or definitions of scripts and style sheets.
    - The HTML <body> element represents the content of an HTML document. There is only one <body> element in a document.
    - What this is basically saying is that everything that goes in the <head> tag is not seen by the user (basically), but is used to include relevant information and dynamic content that is processed by the browser.

    4. Based on the messages from the validator, write the bare-minimum HTML you need to have a "valid" web page.
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <title>element must not be empty</title>
      </head>
      <body>
      </body>
    </html>
