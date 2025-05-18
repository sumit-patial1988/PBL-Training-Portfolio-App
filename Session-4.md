# **Day 4 – Collect & Display: Introduction to Tables and Forms in HTML**

---

## **1. Main Project (PBL Context): Building a Student Portfolio Website**

**Project Vision:**  
By the end of this project-based learning module, learners will build a **personal portfolio website** using **HTML and CSS** that:

- Highlights their academic and personal projects  
- Showcases their skills, achievements, and contact details  
- Incorporates user-friendly and accessible design  
- Can be used for internships, online presence, or academic evaluation

> **Today’s Focus:** Learn how to collect and display structured information using **HTML tables and forms**, setting the foundation for future user interaction.

---

## **2. Today’s Problem Statement (PSBL)**

### **Standard Problem Statement:**
> You want to collect visitor details or feedback through your portfolio. You also want to organize structured data like academic history. How can you do that using just HTML?

### **Rewritten as User Stories:**
- *As a student, I want to display my academic details clearly using tables.*  
- *As a developer, I want to collect visitor messages or inquiries via a form.*  
- *As a user, I want an easy way to input and read structured information.*

---

## **3. Learning Objectives**

By the end of this session, learners will be able to:
- Create and format basic HTML tables to display data  
- Build simple HTML forms to collect user input  
- Use common input types like text, email, textarea, and submit  
- Understand key attributes like `action`, `method`, `placeholder`, `name`, and `value`

---

## **4. Scenario-Based Framing**

> You're adding a **Contact Me** section and a **Qualifications Table** to your portfolio. You want visitors to reach out to you and also see your academic background neatly listed.

---

## **5. Mini Visual Roadmap (Descriptive)**

[Start]
↓
Create a <table> for academic info
↓
Add headers (e.g., Degree, Institute, Year, Grade)
↓
Create a <form> section for contact inputs
↓
Add fields: name, email, message, submit
↓
Test form and table rendering
[End]

---

## **6. Conceptual Explanation (Notes + Code Walkthroughs)**

### 🔹 Tables

- Tags: `<table>`, `<tr>`, `<th>`, `<td>`  
- Add rows for each academic entry

### 🔹 Forms

- Tags: `<form>`, `<input>`, `<label>`, `<textarea>`, `<button>` or `<input type="submit">`  
- Common input types: `text`, `email`, `submit`  
- Useful attributes: `placeholder`, `name`, `value`, `required`

### 🔹 Sample Code:

```html
<section id="education">
  <h2>Education</h2>
  <table border="1">
    <tr>
      <th>Degree</th>
      <th>Institute</th>
      <th>Year</th>
      <th>Grade</th>
    </tr>
    <tr>
      <td>B.Sc. Computer Science</td>
      <td>XYZ University</td>
      <td>2023</td>
      <td>A</td>
    </tr>
  </table>
</section>

<section id="contact">
  <h2>Contact Me</h2>
  <form action="#" method="post">
    <label for="name">Name:</label><br />
    <input type="text" id="name" name="name" placeholder="Your name" required /><br /><br />

    <label for="email">Email:</label><br />
    <input type="email" id="email" name="email" placeholder="Your email" required /><br /><br />

    <label for="message">Message:</label><br />
    <textarea id="message" name="message" rows="4" placeholder="Write something..."></textarea><br /><br />

    <input type="submit" value="Send" />
  </form>
</section>
```
## **7. Hands-On Implementation**
Tasks:
Create an Education section with a table listing at least 2 academic records

Create a Contact Me form with:

Name and Email input fields

A Message textarea

A Submit button

Use appropriate labels, placeholders, and required fields

Preview and validate in browser

## **8. Output-Based Assessment**
✅ Task 1:
Display an HTML table with headings and at least 2 data rows

✅ Task 2:
Build a contact form with 3 fields and a submit button

✅ Task 3:
Ensure proper form structure with labels and accessibility tags

## **9. Interview Preparation (5 Output-Based Questions)**
Q1: Which tag is used to define a table row?
✅ Answer: <tr>

Q2:
Which input type ensures that the user provides a valid email format?
✅ Answer: type="email"

Q3:
Which tag defines a multi-line text input?
✅ Answer: <textarea>

Q4:
What’s the difference between <th> and <td>?
✅ Answer: <th> defines a table header cell; <td> defines a standard data cell.

Q5:
How do you make a form field mandatory?
✅ Answer: Use the required attribute

10. Connection to the Next Problem Statement
Next Up: Your content is rich—now it’s time to style it with CSS.

📌 Next Session:
Problem: “How can I control the layout and design of my forms and tables?”
You will learn:

CSS styling for forms and tables

Spacing, alignment, and font control

Creating visually appealing user interfaces

