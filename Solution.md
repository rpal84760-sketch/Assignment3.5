Plaintext
blog-portfolio/
├── index.html
├── posts.html
└── images/
    ├── desk-setup.jpg
    ├── notes-page.jpg
    └── campus-walk.jpg
1. index.html (Home / Portfolio Overview)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aarav Sharma — Personal Blog &amp; Portfolio</title>
</head>
<body>
  <header>
    <p><strong>Aarav Sharma</strong> &mdash; Personal Blog &amp; Portfolio</p>
    <nav aria-label="Primary navigation">
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="#about-me">About Me</a></li>
        <li><a href="#skills-interests">Skills &amp; Interests</a></li>
        <li><a href="posts.html">Blog &amp; Projects</a></li>
        <li><a href="#gallery">Images</a></li>
        <li><a href="#useful-links">Useful Links</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h1>Welcome to My Portfolio &amp; Notes</h1>

    <section id="about-me">
      <h2>About Me</h2>
      <p>
        I am Aarav Sharma, a computer science student documenting what I learn about web
        foundations, structured markup, and everyday problem solving. This site brings together my
        core skills, study snapshots, and recent blog posts or projects.
      </p>
    </section>

    <section id="skills-interests">
      <h2>Skills &amp; Interests</h2>
      <ul>
        <li>Semantic HTML5 structure and accessible document outlines</li>
        <li>Multi-page linking, relative paths, and asset organization</li>
        <li>Git and GitHub workflows for tracking assignments and projects</li>
        <li>Reading technical guides, debugging layouts, and cycling</li>
      </ul>
    </section>

    <section id="featured-work">
      <h2>Featured Blog Posts &amp; Projects</h2>
      <article>
        <h3>Semantic HTML Foundations Notes</h3>
        <p>
          A structured guide to organizing landmarks, lists, and accessible images in pure HTML.
          Read more on the <a href="posts.html#semantic-html-post">Blog &amp; Projects page</a>.
        </p>
      </article>
      <article>
        <h3>Two-Page &amp; Multi-File Navigation Practice</h3>
        <p>
          An experiment in connecting local HTML files cleanly and opening external references safely.
          See details on the <a href="posts.html#navigation-project">Blog &amp; Projects page</a>.
        </p>
      </article>
    </section>

    <section id="gallery">
      <h2>Images</h2>
      <figure>
        <img
          src="images/desk-setup.jpg"
          alt="Laptop, notebook, and pen on a study desk beside natural light"
          width="600"
          height="400"
        >
        <figcaption>Study desk where I draft HTML outlines and notes.</figcaption>
      </figure>
      <figure>
        <img
          src="images/notes-page.jpg"
          alt="Handwritten notes and page layout boxes in a spiral notebook"
          width="600"
          height="400"
        >
        <figcaption>Planning page sections before writing markup.</figcaption>
      </figure>
      <figure>
        <img
          src="images/campus-walk.jpg"
          alt="Tree-lined campus pathway during morning hours"
          width="600"
          height="400"
        >
        <figcaption>A quick break between study sessions.</figcaption>
      </figure>
    </section>

    <section id="useful-links">
      <h2>Useful Links</h2>
      <ul>
        <li>
          <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noopener noreferrer">
            MDN Web Docs — HTML Reference
          </a>
        </li>
        <li>
          <a href="https://html.spec.whatwg.org/multipage/" target="_blank" rel="noopener noreferrer">
            WHATWG HTML Living Standard
          </a>
        </li>
        <li>
          <a href="https://www.w3.org/WAI/WCAG22/quickref/" target="_blank" rel="noopener noreferrer">
            W3C Accessibility Quick Reference
          </a>
        </li>
      </ul>
    </section>
  </main>

  <footer id="contact">
    <h2>Contact Information</h2>
    <address>
      <p>Email: <a href="mailto:aarav.sharma@example.com">aarav.sharma@example.com</a></p>
      <p>GitHub: <a href="https://github.com/your-username" target="_blank" rel="noopener noreferrer">github.com/your-username</a></p>
      <p>Location: Meerut, Uttar Pradesh, India</p>
    </address>
    <p>&copy; 2026 Aarav Sharma</p>
  </footer>
</body>
</html>
2. posts.html (Dedicated Blog Posts & Projects Page)
HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blog &amp; Projects — Aarav Sharma</title>
</head>
<body>
  <header>
    <p><strong>Aarav Sharma</strong> &mdash; Personal Blog &amp; Portfolio</p>
    <nav aria-label="Primary navigation">
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="index.html#about-me">About Me</a></li>
        <li><a href="index.html#skills-interests">Skills &amp; Interests</a></li>
        <li><a href="posts.html">Blog &amp; Projects</a></li>
        <li><a href="index.html#gallery">Images</a></li>
        <li><a href="index.html#useful-links">Useful Links</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h1>Blog Posts &amp; Projects</h1>

    <section id="blog-posts">
      <h2>Recent Blog Posts</h2>
      <article id="semantic-html-post">
        <h3>Why Semantic HTML Matters First</h3>
        <p>
          Using elements like <code>header</code>, <code>nav</code>, <code>main</code>,
          <code>section</code>, <code>article</code>, and <code>footer</code> gives structure to
          both human readers and assistive tools before any styling is added.
        </p>
      </article>
      <article id="lists-and-links-post">
        <h3>Organizing Content with Lists and Clean Links</h3>
        <p>
          Lists keep skills, resources, and steps easy to scan, while clear link text and safe
          external attributes (<code>target="_blank"</code> with <code>rel="noopener noreferrer"</code>)
          improve usability.
        </p>
      </article>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <article id="navigation-project">
        <h3>Multi-Page Static Site Starter</h3>
        <p>
          A modular set of HTML files connected with relative paths and organized alongside local
          image assets.
        </p>
      </article>
    </section>
  </main>

  <footer id="contact">
    <h2>Contact Information</h2>
    <address>
      <p>Email: <a href="mailto:aarav.sharma@example.com">aarav.sharma@example.com</a></p>
      <p>GitHub: <a href="https://github.com/your-username" target="_blank" rel="noopener noreferrer">github.com/your-username</a></p>
      <p>Location: Meerut, Uttar Pradesh, India</p>
    </address>
    <p>&copy; 2026 Aarav Sharma</p>
  </footer>
</body>
</html>
Committing to GitHub
Place index.html, posts.html, and your images/ folder inside your project directory, then run:

Bash
git init
git add .
git commit -m "Add blog and portfolio mini-project in semantic HTML"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main