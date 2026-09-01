# Semantic HTML5 Elements Guide

A comprehensive web page demonstrating the proper use of semantic HTML5 elements for better accessibility, SEO, and code maintainability.

## What are Semantic HTML Elements?

Semantic HTML elements are elements with meaning. They clearly describe their meaning to both the browser and the developer. Examples include:

- `<header>` - Introductory content or navigation
- `<nav>` - Navigation links
- `<main>` - Main content of the document
- `<article>` - Self-contained content
- `<section>` - Thematic grouping of content
- `<aside>` - Sidebar or related content
- `<footer>` - Footer content

## Benefits

✅ **Improved Accessibility** - Screen readers can better understand page structure
✅ **Better SEO** - Search engines can identify important content
✅ **More Readable Code** - Easier to understand and maintain
✅ **Semantic Structure** - Provides meaningful structure to your content

## Page Structure

The example webpage demonstrates:

1. **Header Section**
   - Site branding and main navigation
   - Uses `<header>` and `<nav>` elements

2. **Main Content**
   - Articles with semantic markup
   - Sections for organizing content
   - Time elements with proper datetime attributes

3. **Sidebar**
   - Complementary content using `<aside>`
   - Quick reference guide

4. **Footer**
   - Contact information using `<address>`
   - Copyright notice
   - Additional links and metadata

## Files

- `index.html` - The main semantic HTML webpage
- `styles.css` - Modern CSS styling with responsive design
- `README.md` - This documentation file

## How to Use

1. Open `index.html` in your web browser
2. Inspect the HTML structure to see semantic element usage
3. Review the CSS for styling best practices
4. Use this as a template for your own semantic HTML projects

## Key Semantic Elements Explained

### &lt;header&gt;
Contains introductory content and navigation for a page or section.
```html
<header>
    <nav><!-- Navigation --></nav>
    <h1>Site Title</h1>
</header>
```

### &lt;nav&gt;
Defines a set of navigation links.
```html
<nav>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#about">About</a></li>
    </ul>
</nav>
```

### &lt;main&gt;
Specifies the main content. Use only once per page.
```html
<main>
    <!-- Main page content -->
</main>
```

### &lt;article&gt;
Independent, self-contained content.
```html
<article>
    <h2>Article Title</h2>
    <p>Article content...</p>
</article>
```

### &lt;section&gt;
Thematic grouping of content.
```html
<section>
    <h2>Section Title</h2>
    <p>Section content...</p>
</section>
```

### &lt;aside&gt;
Content aside from main content (sidebars, callouts).
```html
<aside>
    <h2>Related Information</h2>
    <p>Sidebar content...</p>
</aside>
```

### &lt;footer&gt;
Footer content for a page or section.
```html
<footer>
    <p>&copy; 2026 Company Name</p>
</footer>
```

### &lt;address&gt;
Contact information.
```html
<address>
    Email: <a href="mailto:info@example.com">info@example.com</a>
</address>
```

### &lt;time&gt;
Represents a specific time or date.
```html
<time datetime="2026-09-01">September 1, 2026</time>
```

### &lt;figure&gt; & &lt;figcaption&gt;
For illustrations, diagrams, photos with captions.
```html
<figure>
    <figcaption>Image Description</figcaption>
    <img src="image.jpg" alt="Description">
</figure>
```

## Best Practices

1. **Use semantic elements** instead of generic `<div>` elements when possible
2. **One `<main>` per page** - There should be only one main content area
3. **Logical nesting** - Nest headers within sections and articles appropriately
4. **Meaningful structure** - Use headers to create a clear content hierarchy
5. **ARIA labels** - Add ARIA attributes for additional accessibility when needed
6. **Responsive design** - Ensure semantic markup works on all screen sizes

## Browser Support

All semantic HTML5 elements are well-supported in modern browsers:
- Chrome/Edge ✅
- Firefox ✅
- Safari ✅
- Opera ✅

## References

- [MDN Web Docs - Semantic HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantic_HTML)
- [W3C HTML Standard](https://html.spec.whatwg.org/)
- [Web Accessibility Guidelines](https://www.w3.org/WAI/)

## License

Free to use and modify for educational purposes.
