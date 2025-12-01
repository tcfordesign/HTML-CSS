<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>
  <!-- Visible part with content -->
  <h1>Hi, welcome!</h1>
  <p>Use this HTML repository to help you with your studies. It has been separated into Beginner, Intermediate, and Advanced levels.</p>

  <h2>Beginner</h2>
  <p><b>&lt;!DOCTYPE html&gt;</b> - Tells the browser this is modern HTML.</p>
  <p><b>&lt;html lang="en"&gt;</b> - The root of the page.</p>
  <p><b>&lt;head&gt;</b> - Invisible part with settings (encoding, title, metadata).</p>
  <p><b>&lt;meta charset="UTF-8"&gt;</b> - <b>charset</b> = “character set.” It tells the browser which alphabet/encoding to use when displaying text. UTF-8 supports almost all characters and symbols from every language (letters, accents, emojis, etc.).</p>
  <p><b>&lt;body&gt;</b> - Visible part with the content.</p>
  <p><b>&lt;h1&gt; to &lt;h6&gt;</b> - Headings from most important to least important.</p>
  <p><b>&lt;p&gt;</b> - Paragraph of text.</p>
  <p><b>&lt;a&gt;</b> - Link to another page or section.</p>
  <p><b>&lt;img&gt;</b> - Image displayed on the page.</p>
  <p><b>&lt;br&gt;</b> - Line break; <b>&lt;hr&gt;</b> - horizontal line.</p>
  <p><b>&lt;ul&gt;, &lt;ol&gt;, &lt;li&gt;</b> - Unordered lists, ordered lists, and their items.</p>

  <h3>Example Code</h3>

  <!-- Headings -->
  <h1>Main Title <b>(H1)</b></h1>
  <h2>Subtitle <b>(H2)</b></h2>
  <h3>Section Heading <b>(H3)</b></h3>
  <h4>Subsection <b>(H4)</b></h4>
  <h5>Smaller Heading <b>(H5)</b></h5>
  <h6>Tiny Heading <b>(H6)</b></h6>

  <!-- Paragraph -->
  <p>The <code>&lt;p&gt;</code> represents a paragraph; it's where the text is placed.</p>

  <!-- Links -->
  <p>
    <a href="https://github.com/tcfordesign" target="_blank" rel="noopener">Github - tcfordesign</a>
  </p>

  <!-- Image -->
  <img src="https://raw.githubusercontent.com/tcfordesign/HTML-CSS/d0f57435549b34aa7761f9499d7cc2e6ab4a54f1/TC.jpg" alt="tcfordesign Logo">

  <!-- Line break and horizontal rule -->
  <p>First line<br>Second line after break</p>
  <hr>
  <p>Text after the horizontal line</p>

  <!-- Lists -->
  <h2>Unordered List</h2>
  <ul>
    <li>Apples</li>
    <li>Coco</li>
    <li>Cherries</li>
  </ul>

  <h2>Ordered List</h2>
  <ol>
    <li>First step</li>
    <li>Second step</li>
    <li>Third step</li>
  </ol>

  <!-- Section for internal link -->
  <h2 id="section1">Section 1</h2>
  <p>You jumped here using the internal link above.</p>
</body>
</html>
