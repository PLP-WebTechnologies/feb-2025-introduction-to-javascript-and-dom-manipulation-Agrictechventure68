# Introduction to JavaScript and DOM Manipulation

## Objectives

Write basic JavaScript functions.
Manipulate the DOM dynamically.
Respond to user interactions.

## Instructions

- Create a script.js file and link it to a HTML.
- Structure the document using DOCTYPE, html, head, and body.

>[!NOTE]
>  - Write JavaScript that:
>  - Changes text content dynamically.
>  - Modifies CSS styles via JavaScript.
>  - Adds or removes an element when a button is clicked.


# Tasks
- Create a well-structured HTML5 document.
- Use at least 5 different HTML elements.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamic Content and Styling</title>
    <link rel="stylesheet" href="style.css"> </head>
<body>
    <header>
        <h1>Welcome to My Dynamic Page</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <p id="dynamicText">This is the initial text.</p>
        <button id="changeTextButton">Change Text</button>
        <div id="styledDiv">This div will be styled.</div>
        <button id="addElementButton">Add Element</button>
        <button id="removeElementButton">Remove Element</button>
        <div id="container">
            </div>
    </main>

    <footer>
        <p>&copy; 2025 My Dynamic Page</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
