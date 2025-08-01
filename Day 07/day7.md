### 📅 Day 7 – Registration Form: Finishing Touches & Going Live!

**Progress:**
- ✅ Finished the remaining 25 lessons of Module 4, "Learn HTML Forms by Building a Registration Form" on freeCodeCamp!
- 🏁 Registration form project completed and styled

**New Concepts Learned:**
- Form submission with `<button type="submit">`
- Setting `action` and `method` attributes for data handling
- Adding dropdowns (`<select>`), radio groups, and checkboxes for richer forms
- Using `placeholder` and `autocomplete` for better user experience
- Writing custom input validation patterns
- Organizing form layout with `<fieldset>` and semantic structure
- Final CSS touches: spacing, borders, focus states

**Reflections:**  
Today, I wrapped up the registration form module! I learned how to build a complete, user-friendly form and style it for clarity and accessibility. The final lessons emphasized submitting data, usability, and polish.

**Snippet:**
```html
<fieldset>
  <label for="profile-picture">Upload a profile picture: <input id="profile-picture" type="file" name="file" /></label>
  <label for="age">Input your age (years): <input id="age" type="number" name="age" min="13" max="120" /></label>
  <label for="referrer">How did you hear about us?
    <select id="referrer" name="referrer">
      <option value="">(select one)</option>
      <option value="1">freeCodeCamp News</option>
      <option value="2">freeCodeCamp YouTube Channel</option>
      <option value="3">freeCodeCamp Forum</option>
      <option value="4">Other</option>
    </select>
  </label>
  <label for="bio">Provide a bio:
    <textarea id="bio" name="bio" rows="3" cols="30" placeholder="I like coding on the beach..."></textarea>
  </label>
</fieldset>
```
```css
input,
textarea,
select {
  margin: 10px 0 0 0;
  width: 100%;
  min-height: 2em;
}

input, textarea {
  background-color: #0a0a23;
  border: 1px solid #0a0a23;
  color: #ffffff;
}

.inline {
  width: unset;
  margin: 0 0.5em 0 0;
  vertical-align: middle;
}

input[type="submit"] {
  display: block;
  width: 60%;
  margin: 1em auto;
  height: 2em;
  font-size: 1.1rem;
  background-color: #3b3b4f;
  border-color: white;
  min-width: 300px;
}
