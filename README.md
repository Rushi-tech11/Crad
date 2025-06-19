🔄 Card Progress Animation using HTML & CSS
This project is a modern animated card UI built with pure HTML and CSS. It features four cards with:

A linear gradient progress bar

A rotating circular progress ring

Each card visually represents a loading or processing state. This is useful for dashboards, status indicators, or modern web UI design components.

🧰 Technologies Used
✅ HTML5 – for structuring the cards

🎨 CSS3 – for styling, layout, gradients, and animation

✅ 1. HTML as the Base Structure
HTML is used to structure the content on the web page. It defines the layout and placement of each UI element such as:

The main heading (<h1>)

A container for all cards (<div class="container">)

Individual cards (<div class="card">)

Card content like text and animated sections

✅ 2. Semantic Elements
Even though no advanced tags are used, basic semantic tags are applied:

<h1>: Used to display the title Using HTML, CSS at the top of the page

<p>: Used to label each card (e.g., "Card 1", "Card 2")

<div>: Used to group elements logically for styling and animation using CSS

✅ 3. Reusable Card Components
Each card is created with the same HTML structure. This ensures consistency and makes the code easy to maintain.

html
Copy
Edit
<div class="card">
  <p>Card 1</p>
  <div class="bar"></div>
  <div class="circle"></div>
</div>
.bar represents the horizontal progress bar

.circle represents the circular loading animation

✅ 4. Linking HTML to CSS
The <link> tag is used inside the <head> of the HTML file to connect to the external stylesheet (style.css) which handles all the design and animations.

html
Copy
Edit
<link rel="stylesheet" href="style.css" />
✅ 5. Organized Layout
All cards are placed inside a container div which is styled using Flexbox in CSS to align the cards side by side.

html
Copy
Edit
<div class="container">
  <!-- Cards go here -->
</div>


🧱 1. Web Page Structure
The HTML document begins with a standard structure (<!DOCTYPE html>, <html>, <head>, <body>).

Inside the <head>, the page title is defined and the CSS file is linked.

The <body> contains all visible elements like headings and cards.

🏷 2. Page Heading
A heading is placed at the top using the <h1> tag.

Part of the text (e.g., "HTML" and "CSS") is highlighted using <span> tags for styling.

📦 3. Card Container
A main container (like a <div class="container">) is used to hold all the cards.

This container helps organize the cards in one row using CSS (via Flexbox or Grid).

📇 4. Individual Cards
Each card is created using a <div> element with a class (e.g., card) for styling.

Inside each card:

A <p> tag is used to display the card title (like "Card 1", "Card 2").

A <div class="bar"> is used for the horizontal progress bar.

A <div class="circle"> is used to visually represent a circular animation.



| HTML Element       | Purpose                                         |
| ------------------ | ----------------------------------------------- |
| <h1>             | Main title of the page                          |
| <span>           | Highlight specific parts of the title           |
| <div>            | Container for layout and individual cards       |
| <p>              | Label for each card                             |
| <link>           | Connects external CSS file                      |
| class attributes | Used to apply styles and animations through CSS |


🎨 CSS Theoretical Information (for This Project)
CSS (Cascading Style Sheets) is used to style the HTML structure and apply animations and visual effects. This project relies fully on CSS for the design and animation of the cards.

🔳 1. Page Layout and Background
The entire page is given a dark background color to highlight the glowing animations.

A centered layout is created using Flexbox, which aligns the cards horizontally and centers them on the screen.

A smooth font style is applied using CSS font properties.

🧱 2. Card Styling
Each card is styled with:

A dark semi-transparent background.

Rounded corners using border-radius.

A slight box-shadow to give a glowing or lifted effect.

Equal width and height for consistent card size.

🟨 3. Horizontal Progress Bar (Top Line)
Each card contains a horizontal progress bar:

Created using a div with a fixed height and 100% width.

A linear-gradient background from cyan to yellow is applied.

This gradient moves continuously to give an animated glowing effect using animation and @keyframes.

🔵 4. Circular Progress Indicator
A circular loading effect is achieved by:

Creating a div with a border-radius: 50%.

Only part of the border is visible, with the rest made transparent.

The visible part of the border is given a glowing neon effect using gradients or colored borders.

The circle is animated using CSS transform: rotate() to simulate spinning.

⚙ 5. Animations
CSS @keyframes is used to define animations like:

Continuous rotation of the circular loader.

Moving or glowing progress bar gradient.

The animations are applied using the animation property:

Example: animation: rotate 2s linear infinite;

✨ Effects and Enhancements
Hover effects (if used) can change the scale, shadow, or brightness of cards.

Transitions add smoothness when any property changes.


| CSS Feature           | Used For                         |
| --------------------- | -------------------------------- |
| display: flex       | Align cards horizontally         |
| border-radius       | Rounded cards and circle borders |
| box-shadow          | Card glow effect                 |
| background-gradient | Progress bar animation           |
| @keyframes          | Creating animations              |
| transform: rotate   | Circle rotation effect           |
| animation           | Smooth infinite movement         |
