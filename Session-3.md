
# **Day 3 – Bringing It to Life: Links & Images in HTML**

---

## **1. Main Project (PBL Context): Building a Student Portfolio Website**

**Project Vision:**  
By the end of this project-based learning module, learners will build a **personal portfolio website** using **HTML and CSS** that:

- Showcases their academic and personal projects
- Highlights their skills, interests, and contact information
- Is visually engaging and easy to navigate
- Is shareable for internships, freelance work, or academic review

> **Today’s Focus:** Enhance the portfolio with **hyperlinks** and **images** to make the content richer and more interactive.

---

## **2. Today’s Problem Statement (PSBL)**

### **Standard Problem Statement:**
> You’ve structured and formatted your content well. But without links and images, your portfolio still feels flat. How can you make it more visually appealing and connected?

### **Rewritten as User Stories:**
- *As a student, I want to add images so my portfolio looks more professional and personal.*
- *As a developer, I want to add external and internal links to make my site navigable and interactive.*
- *As a user, I want to view profile pictures, project screenshots, and navigate to external resources easily.*

---

## **3. Learning Objectives**

By the end of this session, learners will be able to:
- Insert and format images using the `<img>` tag
- Create both internal and external hyperlinks using the `<a>` tag
- Understand the use of attributes like `href`, `src`, `alt`, `target`
- Enhance their portfolio with visual and interactive elements

---

## **4. Scenario-Based Framing**

> You're submitting your portfolio for a hackathon. Judges want to click and view your GitHub projects and see screenshots of your work. You need to enhance your webpage with links and images today.

---

## **5. Mini Visual Roadmap (Descriptive)**

```
[Start]
   ↓
Add a profile image in the About Me section
   ↓
Insert screenshots or icons in the Projects section
   ↓
Add external links to GitHub, LinkedIn, etc.
   ↓
Use internal links for smooth navigation within the page
   ↓
Test all images and links
[End]
```

---

## **6. Conceptual Explanation (Notes + Code Walkthroughs)**

### 🔹 Hyperlinks
- Basic syntax: `<a href="URL">Text</a>`
- Open in new tab: `target="_blank"`
- Anchor links: `<a href="#section-id">Go to Section</a>`

### 🔹 Images
- Basic syntax: `<img src="image.jpg" alt="Description" />`
- Add width/height with CSS or inline: `width="200"`
- Always use meaningful `alt` text

### 🔹 Sample Code:
```html
<section id="about">
  <h2>About Me</h2>
  <img src="images/profile.jpg" alt="My Profile Picture" width="150" />
  <p>Hi, I'm <strong>Jane Doe</strong>, a web development enthusiast.</p>
</section>

<section id="projects">
  <h2>Projects</h2>
  <ul>
    <li>
      <strong>Portfolio Website</strong><br>
      <img src="images/portfolio.png" alt="Screenshot of Portfolio" width="200" />
      <br>
      <a href="https://github.com/janedoe/portfolio" target="_blank">View on GitHub</a>
    </li>
  </ul>
</section>

<footer>
  <p>Connect with me:
    <a href="https://linkedin.com/in/janedoe" target="_blank">LinkedIn</a> |
    <a href="#contact">Contact</a>
  </p>
</footer>
```

---

## **7. Hands-On Implementation**

### Tasks:
1. Add a profile picture in the About section using `<img>`
2. Add screenshots for projects with appropriate `alt` text
3. Add hyperlinks to:
   - GitHub repositories
   - LinkedIn profile
   - Internal page sections (e.g., contact form)
4. Test and validate links and image paths

---

## **8. Output-Based Assessment**

✅ Task 1:  
Include at least one image with `alt` text and size control

✅ Task 2:  
Add 2+ external links to GitHub, LinkedIn, etc., with `target="_blank"`

✅ Task 3:  
Use anchor links (`#id`) to navigate to different sections on the same page

---

## **9. Interview Preparation (5 Output-Based Questions)**

### Q1:
What does the `alt` attribute in `<img>` do?

✅ **Answer:** Provides alternative text if the image cannot be displayed and helps with accessibility.

---

### Q2:
Which tag is used to link to another webpage?

✅ **Answer:** `<a>`

---

### Q3:
How do you make a link open in a new tab?

✅ **Answer:** Add `target="_blank"` to the `<a>` tag

---

### Q4:
What happens if the `src` attribute in an `<img>` is incorrect?

✅ **Answer:** The image won’t load and the `alt` text will be displayed instead.

---

### Q5:
What is the correct syntax to add an anchor link to a section with `id="projects"`?

✅ **Answer:** `<a href="#projects">Projects</a>`

---

## **10. Connection to the Next Problem Statement**

> **Next Up:** Now that your content is visually engaging, it's time to **style** it beautifully.

📌 **Next Session:**  
**Problem:** “How can I control the appearance of my content?”  
You will learn:
- How to write CSS
- How to link CSS files
- How to style images, links, and layout
