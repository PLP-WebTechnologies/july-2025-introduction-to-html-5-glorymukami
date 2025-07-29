<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Welcome to a sample HTML5 website using semantic tags, accessibility best practices, and SEO-friendly structure." />
  <meta name="keywords" content="HTML5, semantic HTML, accessibility, SEO, web development" />
  <meta name="author" content="Your Name" />
  <title>Semantic HTML5 Webpage</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header role="banner">
    <nav role="navigation" aria-label="Main Navigation">
      <ul>
        <li><a href="#home" aria-current="page">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <h1 id="home">Welcome to My Semantic Website</h1>
  </header>

  <main role="main">
    <section id="about">
      <h2>About Us</h2>
      <p>We build accessible and SEO-friendly websites using modern HTML5 standards. Our goal is to ensure your site is usable by all visitors and easily discoverable on the web.</p>
    </section>

    <section id="services">
      <h2>Our Services</h2>
      <article>
        <h3>Web Development</h3>
        <p>Custom, responsive, and clean websites tailored to your brand.</p>
      </article>
      <article>
        <h3>Accessibility Audits</h3>
        <p>We ensure your site complies with WCAG guidelines for inclusive access.</p>
      </article>
    </section>

    <section id="contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact Us</h2>
      <form action="#" method="POST" aria-label="Contact Form">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required aria-required="true" />

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required aria-required="true" />

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required aria-required="true"></textarea>

        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>

  <aside role="complementary">
    <h2>Latest News</h2>
    <p>We recently updated our accessibility checklist—check it out to keep your site compliant!</p>
  </aside>

  <footer role="contentinfo">
    <p>&copy; 2025 Your Name. All rights reserved.</p>
  </footer>
</body>
</html>
