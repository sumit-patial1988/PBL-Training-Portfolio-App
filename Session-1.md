# PBL-Training-Portfolio-App

# **Day 1 – What’s in a Page? Understanding HTML Structure**

---

## **1. Main Project (PBL Context): Building a Student Portfolio Website**

**Project Vision:**  
By the end of this project-based learning module, learners will build a **personal portfolio website** using only **HTML and CSS** that:

- Showcases their academic and personal projects
- Highlights their skills and contact information
- Is visually appealing and fully responsive
- Can be shared for internships, freelance work, or academic review

> **Today’s Focus:** Create the basic layout and structure of the portfolio using semantic HTML.

---

## **2. Today’s Problem Statement (PSBL)**

### **Standard Problem Statement:**
> You're a student applying for internships. You want to stand out with a digital portfolio. But how do you even structure a web page to start?

### **Rewritten as User Stories:**
- *As a student, I want a personal webpage where I can present my background, skills, and projects.*
- *As a developer, I want to write clean and semantic HTML that forms the skeleton of my site.*
- *As a learner, I want to understand how HTML tags define content and layout.*

---

## **3. Learning Objectives**

By the end of this session, learners will be able to:
- Understand the role of HTML in webpage structure.
- Use semantic tags like `<header>`, `<nav>`, `<section>`, and `<footer>`.
- Create a basic structure for a portfolio site using only HTML.
- Begin organizing personal content into relevant sections.

---

## **4. Scenario-Based Framing**

> Imagine you’re preparing for your first tech interview. You need a portfolio site that introduces who you are, what you’ve done, and how someone can contact you. There’s no designer—**you are the designer, developer, and content writer.**

You must:
- Build a personal homepage with clearly defined sections
- Organize it with semantic HTML
- Prepare it to style with CSS in the next session

---

## **5. Mini Visual Roadmap (Descriptive)**

```
[Start]
   ↓
Create index.html
   ↓
Add <header> with name and title
   ↓
Create <nav> with links (About, Projects, Skills, Contact)
   ↓
Build <section> blocks for About Me, Projects, Skills, Contact Info
   ↓
Close with a <footer>
   ↓
Validate HTML structure
[End]
```

---

## **6. Conceptual Explanation (Notes + Code Walkthroughs)**

### 🔹 HTML Concepts:
- Page structure using:
  - `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`
  - Semantic elements: `<header>`, `<nav>`, `<section>`, `<footer>`
  - Content tags: `<h1>` to `<h6>`, `<p>`, `<ul>`, `<li>`, `<a>`

### 🔹 Project Skeleton Plan:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Portfolio</title>
</head>
<body>
  <header>
    <h1>Hi, I'm Jane Doe</h1>
    <p>Student | Developer | Dreamer</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m a Computer Science student passionate about building meaningful software.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>Portfolio Website</li>
      <li>Simple ToDo App</li>
    </ul>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <p>HTML, CSS, JavaScript, Git</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: jane@example.com</p>
  </section>

  <footer>
    <p>&copy; 2025 Jane Doe</p>
  </footer>
</body>
</html>
```

---

## **7. Hands-On Implementation**

### Folder Setup:
```
/student-portfolio
  ├── index.html
  └── (style.css – to be added in Day 2)
```

### Implementation Steps:
1. Create `index.html`
2. Add all major semantic tags
3. Fill in content with your own name, background, and details
4. Save and open in a browser
5. Validate HTML using [W3C Validator](https://validator.w3.org/)

---

## **8. Output-Based Assessment**

✅ Task 1:  
Create a complete `index.html` file that contains:
- A `<header>` with your name and tagline
- A `<nav>` with at least 4 sections
- Four `<section>` blocks for About, Projects, Skills, and Contact
- A `<footer>` with copyright

✅ Task 2:  
Host it locally and present it to a peer or mentor.

---

## **9. Interview Preparation (5 Output-Based Questions)**

### Q1:
What’s the purpose of the `<header>` tag in HTML?

✅ **Answer:** It represents the introductory content or navigational links of a section or page.

---

### Q2:
Which tag is used to define navigation links?

✅ **Answer:** `<nav>`

---

### Q3:
What’s the difference between `<section>` and `<div>`?

✅ **Answer:** `<section>` is semantic and indicates a standalone block of content, while `<div>` is non-semantic and used for generic grouping.

---

### Q4:
Which of these tags are semantic?
- a) `<div>`
- b) `<span>`
- c) `<section>`
- d) `<main>`

✅ **Answer:** c) `<section>`, d) `<main>`

---

### Q5:
Is it necessary to include `<!DOCTYPE html>` at the beginning of an HTML file?

✅ **Answer:** Yes, it tells the browser to render the page using HTML5 standards.

---

## **10. Connection to the Next Problem Statement**

> **Next Up:** Structure is important, but **style** makes it shine.

📌 **Next Session:**  
**Problem:** “Why does my page look boring?”  
You will learn:
- How to use **CSS** for layout and visual design
- How to apply styles using classes and IDs
- How to create responsive and clean UI with Flexbox
