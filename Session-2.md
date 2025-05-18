
# **Day 2 – Organizing Content: Text Formatting & Lists in HTML**

---

## **1. Main Project (PBL Context): Building a Student Portfolio Website**

**Project Vision:**  
By the end of this project-based learning module, learners will build a **personal portfolio website** using **HTML and CSS** that:

- Showcases their academic and personal projects
- Highlights their skills and contact information
- Is visually appealing and responsive
- Can be used for job applications and internships

> **Today’s Focus:** Learn how to use HTML text formatting tags and lists to enhance the readability and organization of portfolio content.

---

## **2. Today’s Problem Statement (PSBL)**

### **Standard Problem Statement:**
> You’ve structured your portfolio webpage, but it still looks like a wall of plain text. How can you organize information like skills and projects to improve readability?

### **Rewritten as User Stories:**
- *As a user, I want to see clearly organized content so that I can quickly understand the student’s profile.*
- *As a developer, I want to use text formatting and lists to make content more engaging and skimmable.*
- *As a student, I want to present my achievements and skills in an easy-to-read format.*

---

## **3. Learning Objectives**

By the end of this session, learners will be able to:
- Format text using tags like `<strong>`, `<em>`, `<u>`, and `<br>`
- Create ordered (`<ol>`) and unordered (`<ul>`) lists to present grouped data
- Understand proper use cases for different list types
- Apply lists to the Projects and Skills sections of the portfolio

---

## **4. Scenario-Based Framing**

> You’re finalizing your portfolio to apply for a coding bootcamp. Your mentor advises you to make your skills and experiences pop out with better formatting and bullet points. This session helps you implement that advice.

---

## **5. Mini Visual Roadmap (Descriptive)**

```
[Start]
   ↓
Review existing HTML structure
   ↓
Format About Me text with emphasis (bold/italic)
   ↓
Use unordered list to format skills
   ↓
Use ordered list to display project steps or timeline
   ↓
Preview and validate formatting
[End]
```

---

## **6. Conceptual Explanation (Notes + Code Walkthroughs)**

### 🔹 HTML Text Formatting Tags:
- `<strong>` for bold
- `<em>` for italic
- `<u>` for underline
- `<br>` for line breaks
- `<hr>` for horizontal rules

### 🔹 HTML Lists:
- `<ul>` – Unordered List
- `<ol>` – Ordered List
- `<li>` – List Item

### 🔹 Sample Usage:
```html
<section id="about">
  <h2>About Me</h2>
  <p>
    I'm a <strong>Computer Science</strong> student who loves <em>web development</em>.
    <br>
    My journey started in high school, and I've built several mini projects since then.
  </p>
</section>

<section id="skills">
  <h2>Skills</h2>
  <ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>Git</li>
    <li>Responsive Design</li>
  </ul>
</section>

<section id="projects">
  <h2>Projects</h2>
  <ol>
    <li>Portfolio Website – Built with HTML & CSS</li>
    <li>ToDo App – Simple CRUD operations with JavaScript</li>
  </ol>
</section>
```

---

## **7. Hands-On Implementation**

### Tasks:
1. Update `index.html` file to use:
   - `<strong>`, `<em>`, `<br>` in About Me section
   - `<ul>` and `<li>` in Skills section
   - `<ol>` and `<li>` in Projects section
2. Save and preview in the browser
3. Validate the HTML on [W3C Validator](https://validator.w3.org/)

---

## **8. Output-Based Assessment**

✅ Task 1:  
Use appropriate tags to bold/italicize text in the About section.

✅ Task 2:  
Convert plain skills into an unordered list.

✅ Task 3:  
Convert your project list into an ordered list describing the project timeline or order of completion.

---

## **9. Interview Preparation (5 Output-Based Questions)**

### Q1:
Which tag is used to italicize text?

✅ **Answer:** `<em>`

---

### Q2:
Which tag is used to insert a line break?

✅ **Answer:** `<br>`

---

### Q3:
What is the difference between `<ul>` and `<ol>`?

✅ **Answer:** `<ul>` creates an unordered (bulleted) list; `<ol>` creates an ordered (numbered) list.

---

### Q4:
What does `<strong>` do?

✅ **Answer:** It displays bold text and semantically marks it as important.

---

### Q5:
Is this valid HTML?
```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
</ul>
```

✅ **Answer:** Yes

---

## **10. Connection to the Next Problem Statement**

> **Next Up:** Styling brings your content to life.

📌 **Next Session:**  
**Problem:** “How do I make my site visually appealing?”  
You will learn:
- How to use **CSS** for layout and styling
- How to link external CSS files
- How to style text, lists, and sections for visual impact

