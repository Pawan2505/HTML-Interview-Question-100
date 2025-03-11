### **5. What are semantic elements in HTML5?**

**Semantic elements** in HTML5 are tags that provide meaning to the content they enclose, improving the structure and accessibility of a web page. These elements describe the role of the content they contain, making it easier for both browsers and developers to understand the layout and purpose of different sections.

**Examples of semantic elements**:
- `<header>`: Represents the introductory content or navigational links of a page.
- `<nav>`: Defines navigation links.
- `<main>`: Represents the main content of the document.
- `<section>`: Defines a section of content, such as a group of related articles.
- `<article>`: Represents a self-contained piece of content, like a blog post or news article.
- `<footer>`: Defines the footer of the document, typically containing contact information or copyright.

**Benefits**:
- Improves **SEO** (Search Engine Optimization) as search engines can better understand content structure.
- Enhances **accessibility** for screen readers and assistive technologies.
- Makes the HTML code more **readable** and **maintainable** for developers.

**Example**:
```html
<header>
  <h1>Welcome to My Website</h1>
</header>
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
  </ul>
</nav>
<main>
  <section>
    <h2>Article Title</h2>
    <p>Content of the article...</p>
  </section>
</main>
<footer>
  <p>&copy; 2025 My Website</p>
</footer>
```