# **Day 5 – Structure with Meaning: Semantic HTML & Page Layout Practice**

---

## **1. Main Project (PBL Context): Building a Student Portfolio Website**

**Project Vision:**  
By the end of this project-based learning module, learners will build a **personal portfolio website** using **HTML and CSS** that:

- Showcases their academic background, skills, and projects  
- Is built using best practices in web structure and accessibility  
- Follows modern, semantic, and clean HTML structure  
- Is suitable for resumes, internship applications, and online presence

> **Today’s Focus:** Use **semantic HTML tags** and practice **page layout planning** to improve accessibility, clarity, and maintainability of the website structure.

---

## **2. Today’s Problem Statement (PSBL)**

### **Standard Problem Statement:**
> Your portfolio website is growing—but using only `<div>` and basic tags makes the layout unclear and hard to manage. How can you bring structure, readability, and meaning to your markup?

### **Rewritten as User Stories:**
- *As a developer, I want to use semantic HTML tags so that my code is easier to read and maintain.*  
- *As a student, I want my site to be accessible and logically structured.*  
- *As a user, I want the website layout to be clear and consistent across all pages.*

---

## **3. Learning Objectives**

By the end of this session, learners will be able to:
- Understand the importance of semantic HTML in modern web development  
- Use tags like `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`  
- Structure a multi-section webpage using semantic tags  
- Identify and refactor non-semantic markup for clarity

---

## **4. Scenario-Based Framing**

> You're applying for a developer role at an accessibility-conscious company. Their recruiter checks the structure of your site as part of the evaluation. You realize using correct semantic HTML can improve not only SEO and accessibility but also your credibility as a developer.

---

## **5. Mini Visual Roadmap (Descriptive)**

[Start]
↓
Identify current HTML structure with div-heavy markup
↓
Learn semantic tag purposes and examples
↓
Replace divs with semantic tags where applicable
↓
Ensure layout is logical and accessible
↓
Preview and validate with HTML validator
[End]

php-template
Copy
Edit

---

## **6. Conceptual Explanation (Notes + Code Walkthroughs)**

### 🔹 What is Semantic HTML?

Semantic HTML uses tags that describe the **meaning** of the content inside them, improving **accessibility**, **SEO**, and **developer clarity**.

### 🔹 Common Semantic Tags

- `<header>`: Top of a page or section (title, logo, nav)  
- `<nav>`: Navigation menus  
- `<main>`: Main content block  
- `<section>`: Thematic grouping of content  
- `<article>`: Self-contained pieces (e.g., blog posts, news articles)  
- `<aside>`: Related secondary content (e.g., sidebars)  
- `<footer>`: Page or section footer

### 🔹 Semantic Layout Example

```html
<body>
  <header>
    <h1>Jane Doe Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>I'm a student passionate about building the web.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <article>
        <h3>Portfolio Website</h3>
        <p>HTML/CSS responsive personal site.</p>
      </article>
    </section>

    <aside>
      <h4>Quick Links</h4>
      <ul>
        <li><a href="#skills">Skills</a></li>
      </ul>
    </aside>
  </main>

  <footer>
    <p>&copy; 2025 Jane Doe</p>
  </footer>
</body>
```

## **7. Hands-On Implementation**
Tasks:
- Review your existing portfolio layout
- Identify areas where <div> can be replaced by semantic tags
- Refactor the HTML using appropriate semantic tags
- Ensure the layout and page structure remains intact
- Validate using W3C HTML Validator

## **8. Output-Based Assessment**
✅ Task 1:  
Update the layout to use semantic tags like <main>, <section>, <footer>, etc.

✅ Task 2:  
Refactor one section using <article> and <aside> appropriately

✅ Task 3:  
Ensure navigation and content areas are clearly structured and accessible

## **9. Interview Preparation (5 Output-Based Questions)**
Q1:  
What tag would you use for the main body content of a page?  
✅ Answer: <main>

Q2:  
Which tag should wrap navigational links?  
✅ Answer: <nav>

Q3:  
What’s the difference between <section> and <div>?  
✅ Answer: <section> has semantic meaning; <div> does not.

Q4:  
Where would you use <aside>?  
✅ Answer: To group secondary content like sidebars or related links.

Q5:  
Why is semantic HTML important?  
✅ Answer: It improves accessibility, SEO, and developer readability.

## **10. Connection to the Next Problem Statement**
Next Up: Now that your layout is meaningful, it’s time to make it look amazing with CSS layout tools.

📌 Next Session:  
Problem: “How do I control layout visually?”  
You will learn:
- CSS Flexbox and Grid layout systems
- Responsive design concepts
- Structuring layouts cleanly and visually
