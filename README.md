<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>SubmitPro HTML Course - Thinking Computer Colors</title>
<style>
  body {
    font-family: Arial, sans-serif;
    max-width: 900px;
    margin: 20px auto;
    color:  #87CEEB;
    line-height: 1.6;
    background: #121212;
  }
  h1, h2 {
    color: #C7B8EA;
  }
  nav {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 20px;
  }
  nav button {
    background: #7b5fff;
    border: none;
    color: white;
    padding: 10px 15px;
    border-radius: 6px;
    cursor: pointer;
    transition: background 0.3s ease;
  }
  nav button:hover, nav button.active {
    background: #2a5cff;
  }
  section.module {
    display: none;
  }
  section.module.active {
    display: block;
  }
  textarea {
    width: 100%;
    height: 200px;
    font-family: monospace;
    font-size: 14px;
    padding: 10px;
    border: 1px solid #444;
    border-radius: 8px;
    box-sizing: border-box;
    margin-top: 10px;
    background-color: #2a2a2a;
    color: #eeeeee;
  }
  iframe {
    width: 100%;
    height: 250px;
    border: 1px solid #444;
    margin-top: 15px;
    border-radius: 8px;
    background-color: white;
  }
  button.run-btn {
    background-color: #7b5fff;
    color: #eeeeee;
    border: none;
    padding: 12px 25px;
    font-size: 16px;
    border-radius: 8px;
    cursor: pointer;
    margin-top: 10px;
    transition: background-color 0.3s ease;
  }
  button.run-btn:hover {
    background-color: #2a5cff;
  }
  .quiz {
    background: #2a2a2a;
    border-left: 5px solid #7b5fff;
    padding: 15px 20px;
    margin-top: 30px;
    border-radius: 8px;
    color: #87CEEB;
  }
  .quiz h3 {
    margin-top: 0;
    color: #2a5cff;
  }
  .quiz ol {
    padding-left: 20px;
  }
</style>
</head>
<body>

<h1>SubmitPro HTML Course</h1>

<nav id="moduleTabs">
  <button data-module="1" class="active">Module 1</button>
  <button data-module="2">Module 2</button>
  <button data-module="3">Module 3</button>
  <button data-module="4">Module 4</button>
  <button data-module="5">Module 5</button>
  <button data-module="6">Module 6</button>
  <button data-module="7">Module 7</button>
  <button data-module="8">Module 8</button>
</nav>

<!-- Module 1 -->
<section class="module active" id="module-1">
  <h2>Module 1: Introduction to HTML</h2>
  <p>Welcome to your first lesson on HTML! HTML stands for <strong>HyperText Markup Language</strong> and is the foundation of every webpage.</p>
  <h3>Basic HTML Document Structure</h3>
  <pre>
&lt;!DOCTYPE html&gt;
&lt;html&gt;
  &lt;head&gt;
    &lt;title&gt;My First Page&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;h1&gt;Hello, world!&lt;/h1&gt;
    &lt;p&gt;This is my first webpage.&lt;/p&gt;
  &lt;/body&gt;
&lt;/html&gt;
  </pre>
  <h3>Try It Yourself!</h3>
  <textarea data-editor-id="1">
<!DOCTYPE html>
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
    <p>This is my first webpage.</p>
  </body>
</html>
  </textarea>
  <button class="run-btn" data-run-id="1">Run Code</button>
  <iframe id="preview-1"></iframe>

  <div class="quiz">
    <h3>Quick Quiz</h3>
    <ol>
      <li>What does HTML stand for?</li>
      <li>Which tag contains the visible content of the webpage?</li>
      <li>What is the purpose of the &lt;title&gt; tag?</li>
    </ol>
  </div>
</section>

<!-- Module 2 -->
<section class="module" id="module-2">
  <h2>Module 2: Basic HTML Tags</h2>
  <p>Learn headings, paragraphs, bold, italic, and line breaks.</p>
  <pre>
&lt;h1&gt;Heading 1&lt;/h1&gt;
&lt;p&gt;Paragraph text&lt;/p&gt;
&lt;b&gt;Bold text&lt;/b&gt;
&lt;i&gt;Italic text&lt;/i&gt;
&lt;br&gt; Line break
  </pre>
  <h3>Try It Yourself!</h3>
  <textarea data-editor-id="2">
<!DOCTYPE html>
<html>
  <body>
    <h1>My Heading</h1>
    <h2>Subheading</h2>
    <p>This is a <b>bold</b> word and this is <i>italic</i>.</p>
    <p>This is a paragraph.<br>This is a new line.</p>
  </body>
</html>
  </textarea>
  <button class="run-btn" data-run-id="2">Run Code</button>
  <iframe id="preview-2"></iframe>

  <div class="quiz">
    <h3>Quick Quiz</h3>
    <ol>
      <li>How many heading levels are there in HTML?</li>
      <li>What tag is used to create a paragraph?</li>
      <li>Which tag makes text italic?</li>
    </ol>
  </div>
</section>

<!-- Module 3 -->
<section class="module" id="module-3">
  <h2>Module 3: Links and Images</h2>
  <p>Links make your page interactive; images make it beautiful.</p>
  <pre>
&lt;a href="https://www.submitpro.com"&gt;Visit SubmitPro&lt;/a&gt;
&lt;img src="https://via.placeholder.com/150" alt="Placeholder Image"&gt;
  </pre>
  <h3>Try It Yourself!</h3>
  <textarea data-editor-id="3">
<!DOCTYPE html>
<html>
  <body>
    <a href="https://www.submitpro.com" target="_blank">Visit SubmitPro</a>
    <br><br>
    <img src="https://via.placeholder.com/150" alt="Placeholder Image">
  </body>
</html>
  </textarea>
  <button class="run-btn" data-run-id="3">Run Code</button>
  <iframe id="preview-3"></iframe>

  <div class="quiz">
    <h3>Quick Quiz</h3>
    <ol>
      <li>Which attribute specifies the URL for a link?</li>
      <li>Which tag is used to embed an image?</li>
      <li>What does the alt attribute do?</li>
    </ol>
  </div>
</section>

<!-- Module 4 -->
<section class="module" id="module-4">
  <h2>Module 4: Lists</h2>
  <p>Organize content with lists.</p>
  <pre>
&lt;ul&gt; - Unordered list
&lt;ol&gt; - Ordered list
&lt;dl&gt; - Description list
  </pre>
  <h3>Try It Yourself!</h3>
  <textarea data-editor-id="4">
<!DOCTYPE html>
<html>
  <body>
    <h2>My Shopping List</h2>
    <ul>
      <li>Apples</li>
      <li>Oranges</li>
      <li>Bananas</li>
    </ul>
    <h2>Steps</h2>
    <ol>
      <li>Wake up</li>
      <li>Brush teeth</li>
      <li>Go to work</li>
    </ol>
    <h2>Definitions</h2>
    <dl>
      <dt>HTML</dt>
      <dd>HyperText Markup Language</dd>
      <dt>CSS</dt>
      <dd>Cascading Style Sheets</dd>
    </dl>
  </body>
</html>
  </textarea>
  <button class="run-btn" data-run-id="4">Run Code</button>
  <iframe id="preview-4"></iframe>

  <div class="quiz">
    <h3>Quick Quiz</h3>
    <ol>
      <li>What tag creates an unordered list?</li>
      <li>Which list uses numbers?</li>
      <li>What tag is used for term-definition pairs?</li>
    </ol>
  </div>
</section>

<!-- Module 5 -->
<section class="module" id="module-5">
  <h2>Module 5: Tables</h2>
  <p>Display data in tables.</p>
  <pre>
&lt;table&gt; with &lt;tr&gt;, &lt;th&gt;, &lt;td&gt;
  </pre>
  <h3>Try It Yourself!</h3>
  <textarea data-editor-id="5">
<!DOCTYPE html>
<html>
  <body>
    <table border="1" cellpadding="10">
      <tr>
        <th>Name</th>
        <th>Age</th>
      </tr>
      <tr>
        <td>Alice</td>
        <td>30</td>
      </tr>
      <tr>
        <td>Bob</td>
        <td>25</td>
      </tr>
    </table>
  </body>
</html>
  </textarea>
  <button class="run-btn" data-run-id="5">Run Code</button>
  <iframe id="preview-5"></iframe>

  <div class="quiz">
    <h3>Quick Quiz</h3>
    <ol>
      <li>Which tag creates a table row?</li>
      <li>Which tag is used for table headers?</li>
      <li>How do you add a border to a table?</li>
    </ol>
  </div>
</section>

<!-- Module 6 -->
<section class="module" id="module-6">
  <h2>Module 6: Forms</h2>
  <p>Collect user input with forms.</p>
  <pre>
&lt;form&gt;, &lt;input&gt;, &lt;label&gt;
  </pre>
  <h3>Try It Yourself!</h3>
  <textarea data-editor-id="6">
<!DOCTYPE html>
<html>
  <body>
    <form action="#" method="post">
      <label>Name:</label>
      <input type="text" name="name" placeholder="Your name"><br><br>
      <label>Choose your gender:</label><br>
      <input type="radio" name="gender" value="male"> Male<br>
      <input type="radio" name="gender" value="female"> Female<br><br>
      <label>Pick your favorite fruit:</label><br>
      <input type="checkbox" name="fruit" value="apple"> Apple<br>
      <input type="checkbox" name="fruit" value="banana"> Banana<br><br>
      <input type="submit" value="Submit">
    </form>
  </body>
</html>
  </textarea>
  <button class="run-btn" data-run-id="6">Run Code</button>
  <iframe id="preview-6"></iframe>

  <div class="quiz">
    <h3>Quick Quiz</h3>
    <ol>
      <li>What tag is used to create a form?</li>
      <li>Name two input types used in forms.</li>
      <li>What attribute specifies where form data is sent?</li>
    </ol>
  </div>
</section>

<!-- Module 7 -->
<section class="module" id="module-7">
  <h2>Module 7: Semantic HTML</h2>
  <p>Use meaningful tags for better accessibility and SEO.</p>
  <pre>
&lt;header&gt;, &lt;nav&gt;, &lt;article&gt;, &lt;section&gt;, &lt;footer&gt;
  </pre>
  <h3>Try It Yourself!</h3>
  <textarea data-editor-id="7">
<!DOCTYPE html>
<html>
  <body>
    <header>
      <h1>My Website Header</h1>
    </header>
    <nav>
      <a href="#">Home</a> |
      <a href="#">About</a> |
      <a href="#">Contact</a>
    </nav>
    <section>
      <article>
        <h2>Article Title</h2>
        <p>This is an article about semantic HTML.</p>
      </article>
    </section>
    <footer>
      <p>Footer content goes here.</p>
    </footer>
  </body>
</html>
  </textarea>
  <button class="run-btn" data-run-id="7">Run Code</button>
  <iframe id="preview-7"></iframe>

  <div class="quiz">
    <h3>Quick Quiz</h3>
    <ol>
      <li>Name three semantic HTML tags.</li>
      <li>Why is semantic HTML important?</li>
      <li>Which tag defines navigation links?</li>
    </ol>
  </div>
</section>

<!-- Module 8 -->
<section class="module" id="module-8">
  <h2>Module 8: Multimedia (Audio, Video, Embeds)</h2>
  <p>Add audio, video, and embedded content to your pages.</p>
  <pre>
&lt;audio&gt;, &lt;video&gt;, &lt;iframe&gt;
  </pre>
  <h3>Try It Yourself!</h3>
  <textarea data-editor-id="8">
<!DOCTYPE html>
<html>
  <body>
    <h2>Audio Example</h2>
    <audio controls>
      <source src="https://www.w3schools.com/html/horse.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>

    <h2>Video Example</h2>
    <video width="320" height="240" controls>
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>

    <h2>Embedded Content</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/tgbNymZ7vqY" frameborder="0" allowfullscreen></iframe>
  </body>
</html>
  </textarea>
  <button class="run-btn" data-run-id="8">Run Code</button>
  <iframe id="preview-8"></iframe>

  <div class="quiz">
    <h3>Quick Quiz</h3>
    <ol>
      <li>Which tag is used to embed audio?</li>
      <li>How do you add video to a webpage?</li>
      <li>Which tag embeds content from other websites?</li>
    </ol>
  </div>
</section>

<script>
  // Tab switching
  const tabs = document.querySelectorAll('#moduleTabs button');
  const modules = document.querySelectorAll('section.module');

  tabs.forEach(tab => {
    tab.addEventListener('click', () => {
      // Remove active from all tabs and modules
      tabs.forEach(t => t.classList.remove('active'));
      modules.forEach(m => m.classList.remove('active'));

      // Activate current tab and module
      tab.classList.add('active');
      document.getElementById('module-' + tab.dataset.module).classList.add('active');
    });
  });

  // Run Code buttons
  document.querySelectorAll('button.run-btn').forEach(button => {
    button.addEventListener('click', () => {
      const runId = button.dataset.runId;
      const textarea = document.querySelector(textarea[data-editor-id="${runId}"]);
      const iframe = document.getElementById('preview-' + runId);
      const code = textarea.value;
      const preview = iframe.contentWindow.document;
      preview.open();
      preview.write(code);
      preview.close();
    });
  });

  // Run first module code by default on page load
  window.addEventListener('load', () => {
    document.querySelector('button.run-btn').click();
  });
</script>
<!-- COMPLETE COURSE BUTTON -->
<div id="complete-course-container" style="text-align:center; margin-top:40px;">
  <button onclick="showCertificate()" style="background:#7b5fff; color:white; padding:15px 30px; font-size:18px; border:none; border-radius:8px; cursor:pointer;">
    Complete Course and Get Certificate
  </button>
</div>

<!-- CERTIFICATE SECTION (HIDDEN BY DEFAULT) -->
<div id="certificate-section" style="display:none; margin-top:30px; background:#2a2a2a; padding:20px; border-radius:10px; color:#87CEEB;">
  <h2>Get Your Certificate</h2>
  <label for="studentName">Full Name:</label><br/>
  <input type="text" id="studentName" placeholder="Enter your name" style="width:100%; padding:10px; margin:10px 0; border-radius:5px; border:1px solid #444; background:#121212; color:#fff;" />

  <label for="dob">Date of Birth or ID Number:</label><br/>
  <input type="text" id="dob" placeholder="Enter DOB or ID Number" style="width:100%; padding:10px; margin:10px 0; border-radius:5px; border:1px solid #444; background:#121212; color:#fff;" />

  <button onclick="generateCertificate()" style="background:#7b5fff; color:white; padding:10px 20px; border:none; border-radius:6px; cursor:pointer;">
    Download Certificate
  </button>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<script>
  const { jsPDF } = window.jspdf || {};

  function showCertificate() {
    document.getElementById('certificate-section').style.display = 'block';
    document.getElementById('complete-course-container').style.display = 'none';
    window.scrollTo({ top: document.body.scrollHeight, behavior: 'smooth' });
  }

  function generateCertificate() {
    const name = document.getElementById('studentName').value.trim();
    const dob = document.getElementById('dob').value.trim();

    if (!name || !dob) {
      alert('Please enter both your name and date of birth or ID number.');
      return;
    }

    if (!jsPDF) {
      alert('PDF generation library not loaded.');
      return;
    }

    const doc = new jsPDF({ orientation: 'landscape', unit: 'pt', format: 'a4' });

    doc.setFillColor(43, 43, 43);
    doc.rect(0, 0, doc.internal.pageSize.getWidth(), doc.internal.pageSize.getHeight(), 'F');

    doc.setFontSize(36);
    doc.setTextColor(123, 95, 255);
    doc.setFont('helvetica', 'bold');
    doc.text('Certificate of Completion', doc.internal.pageSize.getWidth() / 2, 100, { align: 'center' });

    doc.setFontSize(18);
    doc.setTextColor(135, 206, 235);
    doc.text('This certifies that', doc.internal.pageSize.getWidth() / 2, 160, { align: 'center' });

    doc.setFontSize(28);
    doc.setTextColor(255, 255, 255);
    doc.setFont('helvetica', 'bolditalic');
    doc.text(name, doc.internal.pageSize.getWidth() / 2, 200, { align: 'center' });

    doc.setFontSize(16);
    doc.setTextColor(135, 206, 235);
    doc.setFont('helvetica', 'normal');
    doc.text('has successfully completed the SubmitPro HTML Course.', doc.internal.pageSize.getWidth() / 2, 240, { align: 'center' });

    doc.setFontSize(14);
    doc.text(ID/DOB: ${dob}, doc.internal.pageSize.getWidth() / 2, 280, { align: 'center' });

    const date = new Date().toLocaleDateString();
    doc.setFontSize(14);
    doc.text(Date: ${date}, doc.internal.pageSize.getWidth() / 2, 310, { align: 'center' });

    doc.setFontSize(12);
    doc.setTextColor(123, 95, 255);
    doc.text('Powered by SubmitPro', doc.internal.pageSize.getWidth() / 2, doc.internal.pageSize.getHeight() - 40, { align: 'center' });

    doc.save(SubmitPro_Certificate_${name.replace(/\s+/g, '_')}.pdf);
  }
</script>
</body>
</html>
