```html
<!-- Understand and using div Tags -->
<div>
  <!-- A generic container for grouping content -->
  <h1>Main Title</h1>
  <!-- Title inside the div -->
  <p>This is a paragraph inside the div.</p>
  <!-- Paragraph inside the div -->
</div>

<!-- Understanding semantic tags - article , section , main , aside , form , footer , header , details , figure -->
<header>
  <!-- Represents introductory content or navigation links -->
  <h1>Website Title</h1>
</header>

<main>
  <!-- Represents the main content of the document -->
  <article>
    <!-- Represents an independent piece of content, like a blog post -->
    <h2>Blog Post Title</h2>
    <p>This is the content of the blog post.</p>
  </article>

  <section>
    <!-- Represents a thematic grouping of content -->
    <h2>Section Title</h2>
    <p>Content related to the section topic.</p>
  </section>

  <aside>
    <!-- Represents related content or a sidebar -->
    <p>This is additional content, like ads or links.</p>
  </aside>
</main>

<footer>
  <!-- Represents footer content -->
  <p>© 2025 Your Website. All rights reserved.</p>
</footer>

<!-- Differentiating between block and inline elements -->
<!-- Block Elements -->
<div>
  <!-- Block element: Takes up the full width of its container -->
  <h1>Block Element Example</h1>
  <!-- Block element: Starts on a new line -->
  <p>Paragraphs are also block elements.</p>
  <!-- Block element: Starts on a new line -->
</div>

<!-- Inline Elements -->
<span>Inline text</span>
<!-- Inline element: Does not start on a new line -->
<a href="#">This is a link</a>
<!-- Inline element: Fits within the flow of surrounding text -->
<strong>This text is bold</strong>
<!-- Inline element: Styles text without breaking the flow -->

<!-- Text formatting tags in HTML - b , string , i , small , ins , sub , sup , del , mark -->
<b>This text is bold.</b>
<!-- Bold text for emphasis -->
<strong>This text is strongly emphasized.</strong>
<!-- Indicates strong importance -->

<i>This text is italicized.</i>
<!-- Italicized text for emphasis or style -->
<small>This text is smaller than normal text.</small>
<!-- Displays smaller-sized text -->

<ins>This text is inserted.</ins>
<!-- Indicates inserted content, often with underline -->
<del>This text is deleted.</del>
<!-- Indicates deleted content, often with a strikethrough -->

<sub>This is subscript text.</sub>
<!-- Displays text below the baseline (e.g., H₂O) -->
<sup>This is superscript text.</sup>
<!-- Displays text above the baseline (e.g., x²) -->

<mark>This text is highlighted.</mark>

<!-- Highlights text for emphasis -->
<mark>This text is highlighted for emphasis.</mark>
<!-- Highlights text with a yellow background by default -->

<!-- Working with HTML Symbols and Special Characters ♣️ © ← -->
<p>
  &#9827; or &clubs;
  <!-- Displays the ♣ symbol (club) -->
</p>
<p>
  &#169; or &copy;
  <!-- Displays the © symbol (copyright) -->
</p>
<p>
  &#8592; or &larr;
  <!-- Displays the ← symbol (left arrow) -->
</p>

<!-- Working with HTML tables - table , td , tr , th -->
<table border="1">
  <!-- Creates a table with a border -->
  <thead>
    <!-- Table head: Contains header rows -->
    <tr>
      <!-- Table header row -->
      <th>Header 1</th>
      <!-- Table header cell -->
      <th>Header 2</th>
      <th>Header 3</th>
    </tr>
  </thead>
  <tbody>
    <!-- Table body: Contains main data rows -->
    <tr>
      <!-- Table data row -->
      <td>Data 1</td>
      <!-- Table data cell -->
      <td>Data 2</td>
      <td>Data 3</td>
    </tr>
    <tr>
      <!-- Another data row -->
      <td>Data 4</td>
      <td>Data 5</td>
      <td>Data 6</td>
    </tr>
  </tbody>
  <tfoot>
    <!-- Table footer: Contains summary or footer rows -->
    <tr>
      <!-- Table footer row -->
      <td colspan="3">Table Footer</td>
      <!-- Spans 3 columns -->
    </tr>
  </tfoot>
</table>
