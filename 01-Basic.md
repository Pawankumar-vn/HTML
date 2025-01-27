<!-- Understanding HTML and its use Cases -->

HTML (HyperText Markup Language) is the standard language for creating web
pages. It structures the content on the web by defining elements like headings,
paragraphs, links, images, and other elements. 
Use Cases: Building Web Pages
Displaying Content Creating Links Embedding Media Building Forms Search Engine
Optimization (SEO)

<!-- Understand HTML Structure -->

<!DOCTYPE html>
<!-- Defines document type (HTML5) -->
<html lang="en">
  <!-- Sets language to English -->
  <head>
    <!--Contains metadata about the page -->
    <meta charset="UTF-8" />
    <!-- Specifies character encoding -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Ensures responsive design -->
    <title>My First Page</title>
    <!-- Sets webpage title -->
  </head>
  <body>
    <!--Contains the visible content of the page -->
  </body>
</html>

<!-- Working with text elements - h tags , p tag , br tag , a tag , span , code , pre -->
 <h1> <!-- Main heading (largest) -->
  <h2> <!-- Subheading -->
  <h3> <!-- Smaller subheading -->
  <p> <!-- Paragraph element -->
  <br> <!-- Line break -->
  <span> <!-- Inline text element -->
  <code> <!-- Displays code in monospaced font -->
  <pre> <!-- Preformatted text (preserves spaces and line breaks) -->
  
<!-- Working with HTML Lists(Ordered & Unordered lists) - ol , ul , li -->
<ol> <!-- Ordered list (numbered items) -->
  <li> <!-- List item -->
  <li> <!-- List item -->
</ol>

<ul> <!-- Unordered list (bulleted items) -->
  <li> <!-- List item -->
  <li> <!-- List item -->
</ul>

<!-- Understanding Concept of nested elements in HTML -->
<ul> <!-- Unordered list -->
  <li>Item 1</li> <!-- List item -->
  <li>Item 2
      <ul> <!-- Nested unordered list -->
          <li>Sub-item 1</li> <!-- Nested list item -->
          <li>Sub-item 2</li> <!-- Nested list item -->
      </ul>
  </li>
  <li>Item 3</li> <!-- List item -->
</ul>

<

<!-- HTML attributes - href , target ,-->
<a href="https://www.example.com" target="_blank">Link</a> <!-- href specifies the link destination, target="_blank" opens in a new tab -->


<!-- Navigating between pages and section using anchor tag -->
<a href="page2.html">Go to Page 2</a> <!-- Link to another page -->

<a href="#section2">Go to Section 2</a> <!-- Link to a section within the same page -->

<!-- A different section on the same page -->
<h2 id="section2">Section 2</h2> <!-- Target section with an ID -->
<p>This is Section 2.</p>

<!-- Comment Code in HTML Document -->
<!-- This is a single-line comment -->

<!-- 
    This is a multi-line comment.
    It can span across multiple lines.
    Use it to explain larger sections of code.
-->

