# EJS Partials
Notes taken from above named article by: Hensle Joseph

## Partials
### Partials allow you to reuse the same HTML across multiple views.
### You can create a file with the EJS code to be used in order to standardize the appearance of multiple pages.  

### This is done using `<%-include(PARTIAL_FILE) %>
### This could be incredibly useful if you want the base of a website to stay consistent throughout all of the pages without having to write the code out for all of the pages.  It would look like this:

```HTML 
  <!-- views/post.ejs -->
    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8">
        <title>POST_TITLE | Node.js Blog</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
        <style>
            body {
                padding-top: 20px;
                padding-bottom: 20px;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <%- include('partials/navbar') %>
            <div>
                <h2>POST_TITLE</h2>
                <p>by <a href="#">POST_AUTHOR</a></p>
                <p>POST_CONTENT</p>
                <hr>
            </div>
            <%- include('partials/footer') %>
        </div>
    </body>
    </html>
```

    