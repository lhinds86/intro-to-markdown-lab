# How to write an HTML Boilerplate

### What is an HTML Boilerplate?
An HTML boilerplate is a starting point for building web pages or web applications. It typically includes essential markup, such as the <!DOCTYPE> declaration, <html>, <head>, and <body> tags, along with commonly used meta tags and scripts. Using a boilerplate can save time by providing a standardized foundation for your projects.

### Creating an HTML Boilerplate

1. Create and Html File with the file extension html.

`index.html`

2. Add the <!DOCTYPE> Declaration
Begin your HTML document with the <!DOCTYPE> declaration to specify the document type and version of HTML you're using. For HTML5, the declaration is:

```html
<!DOCTYPE html>
```

3. Create the `<html>` Element
Next, create the `<html>` element to enclose the entire HTML document.

```html
<html lang="en">
```

4. Add the `<head>` Section
Inside the `<html>` element, create the `<head>` section. This section contains meta-information about the document, such as the title, character encoding, and links to external resources.
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Title Here</title>
</head>
```

5. Include External Stylesheets and Scripts (Optional)
If you're using external CSS stylesheets or JavaScript files, link to them in the `<head>` section using the `<link>` and `<script>` tags, respectively.
```html
<link rel="stylesheet" href="styles.css">
<script src="script.js"></script>
```
Replace `"styles.css"` and `"script.js"` with the paths to your CSS and JavaScript files.

6. Create the `<body>` Section
After the `<head>` section, create the `<body>` section where you'll put the content of your webpage.
```html
<body>
    <!-- Your content goes here -->
</body>
```
7. Closing Tags
Finally, make sure to close all opened tags properly. The closing `</html>` tag should be the last line of your HTML document.

***Example***
Putting it all together, here's a complete example of a basic HTML boilerplate:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Title Here</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js"></script>
</head>
<body>
    <!-- Your content goes here -->
</body>
</html>
```