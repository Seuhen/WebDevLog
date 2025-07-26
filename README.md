# 💻 Shayan's Coding Quest Log 🚀

### 📅 Day 1 – HTML Foundations Begin!

**Progress**: Completed 30 lessons of the "Learn HTML by Building a Cat Photo App" module on freeCodeCamp.  
**Key Concepts Learned**:
- Headings (`<h1>` to `<h6>`)
- Paragraphs & Text Formatting
- Links (`<a href="">`) and Anchor Tags
- Image embedding (`<img src="">`)
- Unordered and Ordered Lists

**Reflections**:  
Today was about rekindling my web dev spark. It felt familiar, but fresh. Understanding how tags work again made me realize how much power simple structure holds. Ready to dive deeper tomorrow!

<!-- Day 1 HTML Snippet -->
<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">
<a href="https://freecodecamp.org">Visit freeCodeCamp</a>

### 📅 Day 2 – From Structure to Style

**Progress:**
- ✅ Completed the HTML module: "Cat Photo App"
- ✅ Reached Lesson 30 of the CSS module: "Café Menu"
- 🧪 Completed Side Quest: Designed and published a custom Character Card for Lucius

---

**New Concepts Learned:**
- Semantic HTML elements and form structure
- CSS fundamentals: colors, fonts, spacing, borders, box model
- How to preview work using GitHub Pages
- Linking assets and writing clean, readable code

---

**Side Quest – Lucius Character Card:**
🧙‍♂️ Created a fully styled HTML/CSS card to represent my original character  
🔗 [Live Preview on GitHub Pages](https://seuhen.github.io/WebDevLog/Day%202/hero-card%20(Side%20Quest).html)

**Card Features:**
- Custom `.jpg` image hosted on GitHub
- Stats layout using `<ul>` and styled `.card` component
- Color palette inspired by Lucius’s arcane tone (dark, teal, soft glow)
- Short backstory for immersion

---

**Snippet:**
```html
<ul class="stats">
  <li>Strength: 16</li>
  <li>Agility: 15</li>
  <li>Wisdom: 20</li>
  <li>Magic: 23</li>
  <li>Luck: 12</li>
</ul>
```

### 📅 Day 3 – CSS in Practice: Selectors, Box Model, and Styling Exploration

**Progress:**
- ✅ Completed up to Lesson 60 of Module 2 (“Responsive Web Design”) on freeCodeCamp
- 🛠️ Enhanced my understanding of layouts, selectors, and responsive units

---

**New Concepts Learned:**
- CSS Selectors: class, id, attribute, and pseudo-selectors
- Box Model mastery: `margin`, `padding`
- Font and their styling
- Display property

---

**Reflections:**  
Today was all about making web pages look good, using different styling fonts and propeties and witnessing the changes happening, seeing it come to life was truly rewarding

---

**Snippet:**
```html
<section>
  <h2>Desserts</h2>
  <article class="item">
    <p class="dessert">Donut</p><p class="price">1.50</p>
  </article>
  <article class="item">
    <p class="dessert">Cherry Pie</p><p class="price">2.75</p>
  </article>
  <article class="item">
    <p class="dessert">Cheesecake</p><p class="price">3.00</p>
  </article>
  <article class="item">
    <p class="dessert">Cinnamon Roll</p><p class="price">2.50</p>
  </article>
</section>
```
```css
.menu {
  width: 80%;
  background-color: burlywood;
  margin-left: auto;
  margin-right: auto;
  padding: 20px;
  max-width: 500px;
}
```

### 📅 Day 4 – Café Menu: Responsive and Ready to Serve & The Mystic Ember Tavern

**Progress:**
- ✅ Completed Module 2 'Cafe Menu' with 91 lessons on freeCodeCamp!
- 🏆 Built and styled a custom tavern menu as a side quest

---

**New Concepts Learned:**
- External stylesheet linking (`styles.css`)  
- `background-image` and layout centering (`width`, `margin`)  
- Class-based styling (`.menu`, `.item`, `.flavor`, `.price`)  
- `display: inline-block` for side-by-side layout  
- Responsive setup via `<meta viewport>`

---

**Side Quest – The Mystic Ember Tavern Menu:**
🍻 Designed a fantasy-themed menu for "The Mystic Ember Tavern", featuring magical elixirs and delicious foods  
🔗 [Live Preview on GitHub Pages](https://seuhen.github.io/WebDevLog/Day%204/Tavern%20Menu%20(Side%20Quest)/tavern_menu.html)

**Menu Features:**
- Responsive layout using Flexbox and media queries
- Themed color palette with warm, ember-inspired tones
- Menu items grouped for elixirs and foods
- Decorative header and custom font

---

**Reflections:**
Today I finally completed the lessons and the menu came to shape. I also made a custom menu for a fantasy tavern in the same way.

**Snippet:**
```html
<h1>Cafe Menu</h1>
<main>
  <section>
    <h2>Coffees</h2>
    <article class="item">
      <p class="flavor">French Vanilla</p><p class="price">3.00</p>
    </article>
    <article class="item">
      <p class="flavor">Caramel Macchiato</p><p class="price">3.75</p>
    </article>
    <article class="item">
      <p class="flavor">Pumpkin Spice</p><p class="price">3.50</p>
    </article>
    <article class="item">
      <p class="flavor">Hazelnut</p><p class="price">4.00</p>
    </article>
    <article class="item">
      <p class="flavor">Mocha</p><p class="price">4.50</p>
    </article>
  </section>
</main>
```
```css
body {
  background-image: url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg);
  font-family: sans-serif;
  padding: 20px;
}
.menu {
  width: 80%;
  background-color: burlywood;
  margin-left: auto;
  margin-right: auto;
  padding: 20px;
  max-width: 500px;
}
.item {
  display: flex;
  justify-content: space-between;
  margin-bottom: 10px;
}
.flavor, .price {
  width: 40%;
}
h1, h2 {
  text-align: center;
}
```
