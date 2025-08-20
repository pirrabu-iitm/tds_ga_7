---
marp: true
theme: custom
paginate: true
style: |
  section {
    font-family: 'Segoe UI', sans-serif;
    color: #333;
  }

  h1 {
    color: #005f73;
  }

  footer {
    font-size: 0.8em;
    color: #666;
  }

  .contact {
    font-size: 0.9em;
    color: #444;
    text-align: right;
    padding-top: 1em;
  }
---

<!-- _class: lead -->

# Product Documentation with Marp

Creating Maintainable, Versioned, and Convertible Docs

<div class="contact">
Email: 23f3004489@ds.study.iitm.ac.in
</div>

---

# Why Use Marp?

- Version control–friendly (Markdown)
- Converts to PDF, HTML, PPTX
- Supports themes, math, and images
- Easy to integrate with CI/CD pipelines

---

<!-- _backgroundImage: url("https://source.unsplash.com/featured/?technology") -->
<!-- _backgroundSize: cover -->

# Visually Appealing Slides

Use background images to enhance visual storytelling.

---

# Algorithmic Complexity

Marp supports LaTeX-style math!

$$
T(n) = O(n \log n)
$$

This is common for efficient sorting algorithms.

---

# Custom Theme

You can define themes in the same file or in external `.css`:

```yaml
theme: custom
