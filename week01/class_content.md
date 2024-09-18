## Setup Activity:

1. **Pairing Up**: Work with a partner and complete steps 1 to 4 together, ensuring that the following are set up:
   - **Visual Studio Code**
   - **Web Browser Extension**
   - **GitHub account**
   - **Git**

2. **Communication**: Instead of using Teams (as suggested in the course), we will use **WhatsApp** and **in-person groups** for communication.

3. **Platform**: Ignore anything related to Canvas or I-learn (BYU-I’s official platform). For this course, we will use **GitHub** to submit activities.

4. **Next Steps**: Once everyone has completed the setup, we will proceed to the next topic.

---

## Course File and Folder Naming Conventions

Follow these best-practice rules for naming files and folders in your coursework:

1. **File Name Structure**: Use a clear and consistent structure for file names.
2. **Lowercase**: Always use lowercase letters in file names.
3. **No Spaces**: Use **dashes** (`-`) instead of spaces.
4. **No Special Characters**: Avoid special characters such as `<, >, \, /, #, ?, !`.

### Folder Naming Conventions:
- **styles**: Use this folder for CSS files.
- **images**: Use this folder for image files.

---

# An Introduction to HTML

## 1. Web Development Basics

### 1.1 The Internet
The **Internet** is a global network of computers that communicate using rules called **protocols**. The most important protocol is **TCP/IP** (Transmission Control Protocol/Internet Protocol).

### 1.2 The World Wide Web (WWW)
The **World Wide Web** (WWW) is a collection of resources, such as documents and applications, connected through **hypertext links**. The **HTTP** (Hypertext Transfer Protocol) is used to access these resources.

### 1.3 How Websites Work
When a user opens a website:
- A **request** is sent to a **web server** (back-end) where the website’s files are stored.
- The user, with their browser (e.g., Chrome, Edge, Safari), is the **client** (front-end).
- A **URL** (Uniform Resource Locator) is entered or clicked.
- The **DNS** (Domain Name System) matches the URL with the correct **IP address**.
- The server then sends the requested files to the client.

### 1.4 Hosting and Domain Names
Web developers can store files on pre-configured servers via hosting companies and link them to a **domain name** (e.g., mycompany.com). They may also manage their own servers.

### 1.5 Front-End vs. Back-End
- **Front-end languages** (e.g., HTML, CSS) run on the client’s device and determine the appearance of a website.
- **Back-end languages** (e.g., PHP, Python) run on the server and handle tasks like user authentication and data processing.

### 1.6 Optimizing for Different Devices
Websites need to be optimized for various devices (phones, tablets, laptops). Developers strive to:
- **Maintain speed** and **efficiency** without sacrificing quality.
- **Ensure accessibility** for users with disabilities (e.g., screen reader support).

---

## 2. What is HTML?

HTML (Hypertext Markup Language) provides the structure for a web page. Below is a simple HTML example:

```html
<body>
    <h1>This is the Main Heading</h1>
    <p>This paragraph is an introduction to the rest of the page.</p>
   
    <h2>This is a Sub-heading</h2>
    <p>This is more information within the sub-heading.</p>
</body>
```

### 2.1 Explanation of HTML Structure
- **Tags**: HTML uses **elements** (tags) within angle brackets. Each tag has an opening (`<tag>`) and closing (`</tag>`).
- **Nesting**: Tags can contain other tags, which is called **nesting**. For example, the `<body>` tag contains headings (`<h1>`, `<h2>`) and paragraphs (`<p>`).

In the example above:
- `<h1>` represents the **main heading**.
- `<h2>` represents a **sub-heading**.
- `<p>` represents a **paragraph**.

### 2.2 HTML as a Markup Language
HTML is a **markup language**, not a programming language. It uses tags to tell web browsers how to display content. Browsers interpret these tags to render the web page.

---

## 3. HTML File Structure

Here's the basic structure of an HTML file:

```html
<!DOCTYPE html> <!-- HTML version declaration -->
<html lang="en-US"> <!-- Start of the HTML document -->
   <head> <!-- Contains metadata about the page -->
      <title>Page Title</title> <!-- Displays in the browser tab, not on the page -->
   </head>
   <body> <!-- Contains the content visible on the page -->
   </body>
</html>
```

### 3.1 Structure Breakdown
- `<!DOCTYPE html>`: Declares that the document is written in **HTML5**.
- `<html>`: The root element that contains all other HTML tags.
- `<head>`: Contains **metadata** (information about the page), like the title displayed in the browser tab.
- `<body>`: Contains the **visible content** of the web page.

### 3.2 Writing HTML Files
HTML files can be written in any text editor, though **code editors** like Visual Studio Code are recommended for ease of use and efficiency.

---

## 4. HTML Elements and Attributes

### 4.1 Common HTML Elements

HTML elements form the building blocks of web pages. We've already seen `<h1>`, `<h2>`, and `<p>` elements. Let’s explore a few more common elements.

#### Parent Elements: `<header>`, `<main>`, and `<footer>`

- **`<header>`**: A parent element placed at the top of the page. It often contains things like the website logo or navigation links and remains consistent across multiple pages. It’s different from the `<head>` element, which is used for metadata.

- **`<main>`**: This element holds the unique content of the web page, such as the primary information or article.

- **`<footer>`**: This element contains content like copyright, contact information, or links, and is typically found at the bottom of the page. Like the `<header>`, it is often consistent across pages.

### 4.2 Child Elements: `<nav>` and `<a>`

- **`<nav>`**: A child element typically placed inside the `<header>`. It contains the navigation menu, usually made up of links.

- **`<a>` (Anchor Tag)**: Used to create **hyperlinks** that navigate the user to another page. The `<a>` element requires an **attribute** to define where the link points to.

### 4.3 Attributes

Attributes provide additional information to HTML elements. They are typically included inside the opening tag and follow the format: `name="value"`.

- **`href` (Hypertext Reference)**: The `href` attribute in the `<a>` tag specifies the destination URL.

Example:
```html
<a href="https://example.com">Click here to go to example.com</a>
```

### 4.4 Image Element: `<img>`

The `<img>` element displays images and is one of the few elements that doesn’t require a closing tag. Instead, it uses attributes to provide all the necessary information.

- **`src` (Source)**: The path to the image file.
- **`alt` (Alternative Text)**: A description of the image, used by screen readers or displayed when the image fails to load.

Example:
```html
<img src="image.jpg" alt="A description of the image">
```

---

## 5. HTML Structure in Code Editors

When writing HTML, it's common to use code editors like **Visual Studio Code**, which color-code different parts of the code:

- **Tags**: Typically in one color (e.g., red).
- **Attribute names**: Often highlighted in another color (e.g., bright red).
- **Attribute values**: Displayed in a different color (e.g., blue).

Here’s a basic HTML document example:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width,initial-scale=l.e">
    <title>Page Title</title>
  </head>
  <body>
    <header>
      <nav>
        <a href="home.html">Home</a>
        <a href="about.html">About</a>
      </nav>
    </header>
    <main>
      <h1>Welcome to My Website</h1>
      <p>This is the main content of the website.</p>
    </main>
    <footer>
      <p>Copyright 2024</p>
    </footer>
  </body>
</html>
```

---

## 6. How HTML is Rendered in Browsers

After writing HTML, browsers like Chrome or Firefox interpret the code to display content. For example:

- The `<h1>` element is rendered as **large, bold text**.
- The `<a>` (anchor) element is rendered as **underlined text** in blue (or purple if the link has been visited).

Browsers apply default styles to these elements using **internal

stylesheets**. This is why headings and links look distinct even before adding your own styles.

---

## 7. Image Optimization for Web Development

Images play a significant role in the overall experience of a website. However, large image files can slow down your website, leading to longer loading times and a poor user experience. To avoid these issues, it's important to optimize images for web development.

### 7.1 How to Optimize Images

1. **Resize Images**: Ensure that your images are not larger than they need to be. For example, if an image is displayed at 500px wide on the screen, don’t upload an image that is 2000px wide.

2. **Use Appropriate File Formats**:
   - **JPEG**: Best for photographs with many colors.
   - **PNG**: Best for images with transparency or fewer colors.
   - **SVG**: Best for vector graphics like logos, as they scale without losing quality.

3. **Compress Images**: Use tools like **TinyPNG** or **JPEG-Optimizer** to reduce the file size of your images without noticeable loss in quality.

4. **Lazy Loading**: Implement **lazy loading** so that images are only loaded when the user scrolls down to them, reducing the initial load time of the web page.

### 7.2 Benefits of Image Optimization

- **Faster Load Times**: Optimized images load faster, which improves the overall speed of the website.
- **Better SEO**: Search engines reward fast-loading websites with better rankings.
- **Improved User Experience**: Users are more likely to stay on a website that loads quickly, especially on mobile devices where data speeds can be slower.

