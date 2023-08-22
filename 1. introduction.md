# Introduction
- **Objective:**  the most popular and powerful front-end (HTML, CSS, and JavaScript) framework for faster and easier responsive web development.
---
- Bootstrap is a free front-end framework for faster and easier web development
- Bootstrap includes HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels and many other, as well as optional JavaScript plugins
- Bootstrap also gives you the ability to easily create responsive designs

Bootstrap was developed by **Mark Otto** and **Jacob Thornton** at Twitter, and released as an open source product in August 2011 on GitHub.

In June 2014 Bootstrap was the No.1 project on GitHub!.

---
### Advantages of Bootstrap
- **Save lots of time**  — You can save lots of time and efforts using the Bootstrap predefined design templates and classes and concentrate on other development work.
- **Responsive features**  — Using Bootstrap you can easily create responsive websites that appear more appropriately on different devices and screen resolutions without any change in markup.
- **Consistent design**  — All Bootstrap components share the same design templates and styles through a central library, so the design and layout of your web pages will be consistent.
- **Easy to use**  — Bootstrap is very easy to use. Anybody with the basic working knowledge of HTML, CSS and JavaScript can start development with Bootstrap.
- **Compatible with browsers** — Bootstrap is created with modern web browsers in mind and it is compatible with all modern browsers such as Chrome, Firefox, Safari, Internet Explorer, etc.
- **Open Source** — And the best part is, it is completely free to download and use.

>**Note:** Bootstrap 4 is responsive by default with a mobile first approach. Bootstrap 4.3 is the latest and most stable version of the Bootstrap. Bootstrap 4 is supported in all major modern browsers such Google Chrome, Firefox, Safari, Internet Explorer 10 and above, etc.

### Ways to use Bootstrap
There are two ways to start using Bootstrap on your own web site.

- Download Bootstrap from [getbootstrap.com](https://getbootstrap.com/)
- Include Bootstrap from a CDN

### Downloading Bootstrap
If you want to download and host Bootstrap yourself, go to [getbootstrap.com](https://getbootstrap.com/), and follow the instructions there.

### Bootstrap CDN
If you don't want to download and host Bootstrap yourself, you can include it from a CDN (Content Delivery Network).

MaxCDN provides CDN support for Bootstrap's CSS and JavaScript. You must also include jQuery:

```html
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">

<!-- jQuery library -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<!-- Latest compiled JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
```
---

### Creating Your First web Page with Bootstrap
In this we are gonna show how to create a basic Bootstrap template by including the Bootstrap CSS and JS files, as well as other JavaScript dependencies like jQuery and Popper.js via CDN.

We recommend adding Bootstrap in your project via CDN (Content Delivery Network) **because CDN offers performance benefit by reducing the loading time**, since they are hosting the files on multiple servers spread across the globe so that when a user requests the file it will be served from the server nearest to them. 

---
### Sept 1: Creating a Basic HTML file
Open up your favorite code editor and create a new HTML file. Start with an empty window and type the following code and save it as "basic.html" on your desktop

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Basic HTML File</title>
</head>
<body>
    <h1>Hello, world!</h1>
</body>
</html>
```

### Step 2: Making this HTML File a Bootstrap Template
In order to make this plain HTML file a Bootstrap template, just include the Bootstrap CSS and JS files as well as required jQuery and Popper.js using their CDN links.

You should include JavaScript files at the bottom of the page, right before the closing \</body> tag to improve the performance of your web pages,

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Basic Bootstrap Template</title>
    <!-- Bootstrap CSS file -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
</head>
<body>
    <h1>Hello, world!</h1>
    <!-- JS files: jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script>
</body>
</html>
```
### Step 3:  Saving and Viewing the File
Now save the file on your desktop as "bootstrap-template.html"

To open this file in a web browser, navigate to it, then right click on it, and select your favorite web browser. Alternatively, you can open your browser and drag this file to it.

---
