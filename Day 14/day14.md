### 📅 Day 14 – Accessibility with a Quiz Webpage

**Progress:**  
✅ Completed the entire "Learn Accessibility by Building a Quiz" module  
✅ Built a fully accessible quiz webpage using semantic HTML and CSS  
✅ Implemented accessibility features including ARIA attributes and keyboard navigation  
✅ Applied design best practices to support users with diverse needs

**Reflections 🧠**  
This module was a powerful reminder that good design is inclusive design. I learned how accessibility isn’t just about screen readers—it’s about building interfaces that work for everyone. The quiz project helped me understand how semantic markup, ARIA roles, and thoughtful keyboard shortcuts can make a real difference. It’s a mindset shift I’ll carry into every future project.

**Dev Mood 💬**  
Empowered, thoughtful, and committed to inclusive design

**Snippet 🔍**  
```html
<section role="region" aria-labelledby="css-questions">
  <h2 id="css-questions">CSS</h2>
  <div class="formrow">
    <div class="question-block">
      <label for="selector">Can the CSS margin property accept negative values?</label>
    </div>
    <div class="answer">
      <select name="selector" id="selector" required>
        <option value="">Select an option</option>
        <option value="yes">Yes</option>
        <option value="no">No</option>
      </select>
    </div>
    <div class="question-block">
      <label for="css-textarea">Do you have any questions:</label>
    </div>
    <div class="answer">
      <textarea id="css-textarea" name="css-questions" rows="5" cols="24"></textarea>
    </div>
  </div>
</section>
```
```css
@media (prefers-reduced-motion: no-preference) {
  * {
    scroll-behavior: smooth;
  }
}

body {
  background: #f5f6f7;
  color: #1b1b32;
  font-family: Helvetica;
  margin: 0;
}

header {
  width: 100%;
  height: 50px;
  background-color: #1b1b32;
  display: flex;
  justify-content: space-between;
  align-items: center;
  top: 0;
}

#logo {
  width: max(10rem, 18vw);
  background-color: #0a0a23;
  aspect-ratio: 35 / 4;
  padding: 0.4rem;
}

h1 {
  color: #f1be32;
  font-size: min(5vw, 1.2em);
  text-align: center;
}

nav {
  width: 50%;
  max-width: 300px;
  height: 50px;
}

nav > ul {
  display: flex;
  justify-content: space-evenly;
  flex-wrap: wrap;
  align-items: center;
  padding-inline-start: 0;
  margin-block: 0;
  height: 100%;
}
```
