# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.
/* General styling for the page */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
    text-align: center;
}

/* Styling for headings */
h1 {
    color: #333;
    font-size: 28px;
    margin-bottom: 20px;
}

/* Styling for paragraphs */
p {
    color: #555;
    font-size: 16px;
    line-height: 1.6;
}

/* Styling an image */
img {
    width: 300px;
    height: auto;
    border: 5px solid #333;
    border-radius: 10px;
    margin: 20px auto;
    display: block;
}

/* Styling a specific class */
.card {
    background-color: white;
    padding: 20px;
    margin: 20px auto;
    width: 60%;
    border: 2px solid #ddd;
    border-radius: 10px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

/* Styling a specific ID */
#highlight {
    color: #e44d26;
    font-weight: bold;
    font-size: 18px;
}

Happy Coding! 💻✨
