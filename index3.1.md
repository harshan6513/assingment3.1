# ASSIGNMENT 3.1
## Two-Page Website with Working Links

**Objective:** To create a two-page website using HTML and connect both pages through working navigation links.

### 1. Introduction

A website can contain multiple web pages connected through hyperlinks. In this assignment, I created a simple two-page website using HTML. The website contains a Home page and an About page. Both pages are connected using navigation links. I also added an external link to MDN Web Docs.

### 2. Software Required

1. Visual Studio Code or Notepad
2. Google Chrome or Microsoft Edge
3. Live Server extension (if using VS Code)

### 3. Project Structure

Create a folder named `assignment-3.1` and create these two files inside it:

- `index.html`
- `about.html`

### 4. Code for index.html (Home Page)

Copy the following code into `index.html`:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website - Home</title>
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>

        <nav>
            <a href="index.html">Home</a> |
            <a href="about.html">About</a>
        </nav>
    </header>

    <hr>

    <main>
        <h2>Home Page</h2>

        <p>Hello! Welcome to my first two-page website.</p>

        <p>This website is created using HTML. You can visit
        the About page to learn more about me.</p>

        <h3>Learn HTML</h3>

        <p>Visit the following website to learn more about HTML:</p>

        <a href="https://developer.mozilla.org/en-US/docs/Web/HTML"
           target="_blank"
           rel="noopener noreferrer">
            MDN Web Docs
        </a>
    </main>

    <hr>

    <footer>
        <p>Created for Assignment 3.1</p>
    </footer>

</body>
</html>
```

### 5. Code for about.html (About Page)

Copy the following code into `about.html`:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website - About</title>
</head>
<body>

    <header>
        <h1>About Me</h1>

        <nav>
            <a href="index.html">Home</a> |
            <a href="about.html">About</a>
        </nav>
    </header>

    <hr>

    <main>
        <h2>Introduction</h2>

        <p>My name is Harsh. I am learning web development.</p>

        <h2>Education</h2>

        <p>I am interested in learning HTML, CSS, and JavaScript.</p>

        <h2>My Interests</h2>

        <ul>
            <li>Learning Programming</li>
            <li>Creating Websites</li>
            <li>Exploring New Technologies</li>
        </ul>

        <p>
            <a href="index.html">Return to Home Page</a>
        </p>
    </main>

    <hr>

    <footer>
        <p>Thank you for visiting my website!</p>
    </footer>

</body>
</html>
```

### 6. Steps to Run the Website

1. Create a folder named `assignment-3.1`.
2. Create two files: `index.html` and `about.html`.
3. Paste the corresponding HTML code into each file.
4. Save both files with the `.html` extension.
5. Open `index.html` in a web browser or use Live Server in VS Code.
6. Click the **About** link to open the About page.
7. Click the **Home** link to return to the Home page.
8. Click **MDN Web Docs** to open the external website in a new tab.

### 7. Important HTML Concepts Used

- **`<a>` tag:** Creates hyperlinks.
- **`href` attribute:** Specifies the destination of a link.
- **`target="_blank"`:** Opens an external link in a new tab.
- **`<nav>` tag:** Defines the navigation section.
- **`<header>` tag:** Defines the header of a page.
- **`<main>` tag:** Contains the main content.
- **`<footer>` tag:** Defines the footer.
- **`<ul>` and `<li>` tags:** Create an unordered list.
- **`<hr>` tag:** Adds a horizontal line.
- **`<title>` tag:** Sets the title shown in the browser tab.

### 8. Testing and Verification

The website should be tested to verify that:

1. The Home page opens correctly.
2. The About link opens `about.html`.
3. The Home link returns to `index.html`.
4. The external MDN Web Docs link opens in a new tab.
5. Both pages display their correct headings and content.

### 9. Screenshots Required

Take actual screenshots from your computer showing:

1. The Home page open in the browser.
2. The About page open in the browser.
3. The project folder containing both HTML files.

### 10. Result

Successfully created a two-page website using HTML. Both pages are connected through working navigation links, and an external hyperlink opens MDN Web Docs in a new browser tab.

### 11. Conclusion

This assignment helped me understand how to create multiple HTML pages, connect them using hyperlinks, organize webpage content, and test website navigation in a browser.

**Assignment Completed Successfully.**