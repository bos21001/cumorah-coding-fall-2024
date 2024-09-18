### **HTML File 1: Incorrect Nesting and Missing Closing Tags**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Debug Challenge 1</title>
  </head>
  <body>
    <header>
      <h1>Welcome to the Website</h1>
      <nav>
        <ul>
          <li><a href="index.html">Home</li>
          <li><a href="about.html">About</li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
    </header>
    
    <main>
      <section>
        <h2>About Us</h2>
        <p>This website is designed to teach HTML and debugging skills.
        <div>
          <h3>Our Mission</h3>
          <p>To help students become better web developers.</p>
      </section>
    </main>
    
    <footer>
      <p>&copy; 2024 Web Dev Challenge<p>
    </footer>
```

**Mistakes**:
1. Missing `</a>` closing tags in the first two `<a>` elements inside the `<li>`.
2. The `<div>` tag is incorrectly nested inside the `<p>`.
3. The `<footer>` has a missing `</p>` closing tag.
4. Body and html are not closed

---

### **HTML File 2: Incorrect Attribute Values and Missing Tags**

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, intial-scale=1.0">
    <title>Debug Challenge 2</title>
  </head>
  <body>
    <header>
      <h1>Debugging Challenge</h1>
      <img src="image.jpg" alt="">
    </header>

    <main>
      <h2>Our Services</h2>
      <p>We offer a range of services to enhance your web development skills, including:
        <ul>
          <li>HTML & CSS training
          <li>JavaScript tutorials
          <li>Debugging exercises
        </ul>
    </main>
    
    <footer>
      <p>Contact us at: <a href="mailto:webdev@example.com">webdev@example.com<a></p>
    </footer>
  </body>
</html>
```

**Mistakes**:
1. The `meta` tag has a typo in `initial-scale` (`intial-scale`).
2. The `<img>` tag is missing an `alt` description.
3. The `<ul>` list items (`<li>`) are not properly closed.
4. The `<a>` tag inside the `<footer>` is missing a closing tag.

---

### **HTML File 3: Mixed Semantic Errors and Styling Issues**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Debug Challenge 3</title>
  </head>
  <body>
    <header>
      <h1>Website Debugging Challenge</h1>
      <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="services.html" Services</a>
      </nav>
    </header>

    <main>
      <article>
        <h2>Our Team</h2>
        <img src="team.jpg" alt="Team photo>
        <p>Meet the team behind the website.</p>
        <div>
          <h3>Team Members</h3>
          <p>John Doe, Jane Doe, and Alex Smith are our core developers.
        </div>
      </article>
    </main>

    <footer>
      <p>Copyright 2024</p>
  </body>
</html>
```

**Mistakes**:
1. In the `<a>` tag for "Services," the closing `>` is misplaced.
2. The `<img>` tag for the team photo is missing a closing quotation mark on the `alt` attribute.
3. The `<p>` inside the `<div>` is not properly closed.
4. The `<footer>` tag is not properly closed.

---

### **Summary of Errors for Each HTML File**:
- **HTML File 1**: Issues with incorrect nesting, missing closing tags, and missing end tags in the footer.
- **HTML File 2**: Problems with incorrect attribute values, missing closing tags for list items and anchor tags.
- **HTML File 3**: Typographical errors in the anchor and image tags, and issues with unclosed tags in the body content.

These files will give students the opportunity to explore debugging using browser tools, correct the errors, and understand how each mistake affects the page rendering.