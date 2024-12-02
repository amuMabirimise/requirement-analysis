# Semantic HTML: Best Practices for Accessibility and SEO

**Level**: Novice  
**Weight**: 1  
**Project Timeline**:

- **Start**: Dec 1, 2024, 11:00 PM
- **End**: Dec 8, 2024, 11:00 PM

### Important Details

- **Checker Release**: Dec 1, 2024, 11:00 PM
- **Manual QA**: Must request manual QA review upon project completion.
- **Auto Review**: Automatically triggered at the project deadline.

---

## Quiz Questions

🎉 **Great! You've completed the quiz successfully! Keep going!**  
*(Click to show quiz)*

---

## Tasks

### 0. Creating a Structured HTML Document Using Semantic Elements

**Objective**: Practice structuring a simple HTML document using semantic elements.

1. Create a file: `0-index.html`.
2. Structure the file:
   - Include `html` tags with `head` and `body` tags (empty initially).
   - Inside the `body` tag:
      - Add a `header` containing a `nav` with at least three links.
      - Create a `main` section containing an `article`:
         - Add an `h1` tag for the title and a `section` for content.

      - Add a `footer` with copyright information: `@copyright`.

3. Ensure the document starts with the `<!DOCTYPE html>` declaration.

**Repository**:

- **GitHub Repository**: `alx-intermediate-frontend`
- __Directory__: `0x00-semantic_html`
- **File**: `0-index.html`

---

### 1. Enhancing HTML Document with Meta Tags and Title for SEO and Accessibility

**Objective**: Enhance the structure of the HTML document with meta tags for SEO, accessibility, and responsiveness.

1. Copy `0-index.html` into `1-index.html`.
2. In the `<head>` tag:
   - Add the `charset="utf-8"` attribute.
   - Add the following meta tags:
      - `name="description"` with `content="A blog post about semantic HTML and accessibility practices"`.
      - `name="keywords"` with `content="HTML, Semantic, Accessibility, Blog, SEO"`.
      - `name="author"` with your name as the content.
      - `name="viewport"` with `content="width=device-width, initial-scale=1.0"`.

   - Add a `<title>`: `Semantic Html Blog Post`.

**Repository**:

- **GitHub Repository**: `alx-intermediate-frontend`
- __Directory__: `0x00-semantic_html`
- **File**: `1-index.html`

---

### 2. Creating a Blog Post Layout Using Semantic HTML Elements

**Objective**: Apply semantic elements to create a blog post layout.

1. Copy `1-index.html` into `2-index.html`.
2. In the `<header>` tag:
   - Add an `h1` with `My Blog`.
   - Add a `nav` containing a `ul` with three `li` elements:
      - Links: `Home`, `About`, and `Contact`.

3. In the `article` inside the `main` tag:
   - Add a `header` with an `h2`: `Understanding Semantic Html`.
   - Add a `p`: `Published on <time datetime="2024-09-10">September 10</time>`.
   - Add sections:
      - Section 1:
         - `h3`: `Introduction`.
         - `p`: Semantic HTML helps improve the accessibility and SEO of your website. In this post, we’ll explore its benefits and how to implement it.

      - Section 2:
         - `h3`: `Main Content`.
         - `p`: Using elements like `<article>`, `<section>`, and `<header>` ensures that both users and search engines can better understand the structure and content of a webpage.
         - Add a `figure`:
            - `img` with an `alt`: `example`.
            - `figcaption`: `An illustration of semantic HTML elements`.

      - Section 3:
         - `h3`: `Conclusion`.
         - `p`: By adopting semantic HTML, you enhance your site's accessibility, improve SEO, and make the content easier to navigate.

   - Add a `footer` with:
      - `p`: `Written by <name>`.
      - `p`: `Published on 2024-09-11`.

**Repository**:

- **GitHub Repository**: `alx-intermediate-frontend`
- __Directory__: `0x00-semantic_html`
- **File**: `2-index.html`

---

### 3. Enhancing Form Accessibility with ARIA Roles and Attributes

**Objective**: Implement ARIA roles to improve accessibility in a form.

1. Copy `2-index.html` into `3-index.html`.
2. Inside the `<main>` tag, add a new `<section>` with a `<form>`:
   - Attributes:
      - `action="#"`
      - `method="POST"`
      - `aria-labelledby="form-title"`
      - `role="form"`

3. Inside the `<form>`:
   - Add a `div` with:
      - `label` for `"name"`.
      - `input` attributes:
         - `type="text"`, `id="name"`, `name="name"`, `aria-required="true"`.

   - Add a second `div` with:
      - `label` for `"email"`.
      - `input` (similar attributes as the above but for `"email"`).

   - Add a third `div` with:
      - `button` attributes:
         - `type="submit"`, `aria-label="Submit the form"`.

   - Add a fourth `div` with:
      - `aria-live="polite"` and `role="alert"`.

**Repository**:

- **GitHub Repository**: `alx-intermediate-frontend`
- __Directory__: `0x00-semantic_html`
- **File**: `3-index.html`

---

### 4. Manual Review

**Mandatory**: Submit your project for manual QA review after completion.

**Repository**:

- **GitHub Repository**: `alx-intermediate-frontend`
- __Directory__: `0x00-semantic_html`