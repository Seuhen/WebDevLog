### 📅 Day 6 – Forms: Building Bridges for User Input

**Progress:**
- ✅ Completed 40 out of 65 lessons from Module 4, "Learn HTML Forms by Building a Registration Form" on freeCodeCamp!

**New Concepts Learned:**
- Creating and organizing `<form>` elements
- Adding input fields: text, email, password, and more
- Using `<label>` for accessibility and form clarity
- Grouping inputs with `<fieldset>` and `<legend>`
- Setting required fields and input validation basics
- Exploring radio buttons, checkboxes, and dropdowns

**Reflections:**  
Today was all about interaction! I learned how to build the structure for user input, making web pages not just informative but also functional. Using proper labels and grouping made the form more accessible.

**Snippet:**
```html
<fieldset>
  <label for="first-name">Enter Your First Name: <input id="first-name" type="text" required /></label>
  <label for="last-name">Enter Your Last Name: <input id="last-name" type="text" required /></label>
  <label for="email">Enter Your Email: <input id="email" type="email" required /></label>
  <label for="new-password">Create a New Password: <input id="new-password" type="password" pattern="[a-z0-5]{8,}" required /></label>
</fieldset>
```
