### 📅 Day 8 – Survey Forms: Gathering Guild Wisdom

**Progress**:  
✅ Designed and built a themed survey form project: "Guild Member Preferences Survey" (see `Day 8/day8 (Survey_Form).html`).  
✅ Practiced advanced HTML form controls: dropdowns, radio buttons, checkboxes, fieldsets, and textarea.

**Key Concepts Learned**:
- Grouping related inputs with `<fieldset>` and `<legend>`
- Using required fields for validation
- Input types: text, email, number
- Dropdown menus for selection (`<select>`)
- Radio buttons for single-choice questions
- Checkboxes for multi-choice options
- Textareas for open-ended responses
- Structuring forms for clarity and accessibility
- Theming and narrative-driven form design

**Reflections:**  
Today was all about creating interactive forms that collect user preferences in a fun, fantasy guild setting. I learned how to organize questions using fieldsets, properly label each input, and offer a themed experience.

**Snippet:**
```html
<form id="survey-form">
  <fieldset>
    <legend>Guild Enrollment</legend>
    <label id="name-label" for="name">Adventurer Name:</label>
    <input type="text" id="name" name="name" placeholder="e.g. Seuhen the Swift" required>

    <label id="email-label" for="email">Magic Messenger Scroll (Email):</label>
    <input type="email" id="email" name="email" placeholder="e.g. seuhen@guildmail.com" required>

    <label id="number-label" for="number">Guild Rank (1–10):</label>
    <input type="number" id="number" name="rank" min="1" max="10" placeholder="Enter your rank">
  </fieldset>

  <fieldset>
    <legend>Adventuring Preferences</legend>
    <label for="dropdown">Preferred Quest Type:</label>
    <select id="dropdown" name="quest">
      <option value="exploration">Exploration</option>
      <option value="combat">Combat</option>
      <option value="puzzle">Puzzle Solving</option>
    </select>
    <p>How often do you visit the Guild Hall?</p>
    <label><input type="radio" name="visit" value="daily"> Daily</label>
    <label><input type="radio" name="visit" value="weekly"> Weekly</label>
    <label><input type="radio" name="visit" value="rarely"> Rarely</label>
  </fieldset>

  <fieldset>
    <legend>Guild Persona</legend>
    <p>Which roles would you consider joining?</p>
    <label><input type="checkbox" value="healer"> Healer</label>
    <label><input type="checkbox" value="tank"> Tank</label>
    <label><input type="checkbox" value="bard"> Bard</label>
    <label><input type="checkbox" value="merchant"> Merchant</label>
    <label for="comments">Describe your ideal guild companion:</label>
    <textarea id="comments" name="comments" placeholder="Tell us about your dream ally..."></textarea>
  </fieldset>
  <button id="submit" type="submit">Send to the Scribes</button>
</form>
