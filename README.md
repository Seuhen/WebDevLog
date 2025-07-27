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

---

### 📅 Day 2 – From Structure to Style

**Progress:**
- ✅ Completed the HTML module: "Cat Photo App"
- ✅ Reached Lesson 30 of the CSS module: "Café Menu"
- 🧪 Completed Side Quest: Designed and published a custom Character Card for Lucius

**New Concepts Learned:**
- Semantic HTML elements and form structure
- CSS fundamentals: colors, fonts, spacing, borders, box model
- How to preview work using GitHub Pages
- Linking assets and writing clean, readable code

**Side Quest – Lucius Character Card:**
🧙‍♂️ Created a fully styled HTML/CSS card to represent my original character  
🔗 [Live Preview on GitHub Pages](https://seuhen.github.io/WebDevLog/Day%202/hero-card%20(Side%20Quest).html)

**Card Features:**
- Custom `.jpg` image hosted on GitHub
- Stats layout using `<ul>` and styled `.card` component
- Color palette inspired by Lucius’s arcane tone (dark, teal, soft glow)
- Short backstory for immersion

**Snippet:**
```html
<main>
  <h1>CAMPER CAFE</h1>
    <p>Est. 2020</p>
      <section>
        <h2>Coffee</h2>
          <article>
            <p>French Vanilla</p>
            <p>3.00</p>
          </article>
      </section>
</main>
```
```css
.menu {
  width: 80%;
  background-color: burlywood;
  margin-left: auto;
  margin-right: auto;
}
```

---

### 📅 Day 3 – CSS in Practice: Selectors, Box Model, and Styling Exploration

**Progress:**
- ✅ Completed up to Lesson 60 of Module 2 (“Responsive Web Design”) on freeCodeCamp
- 🛠️ Enhanced my understanding of layouts, selectors, and responsive units

**New Concepts Learned:**
- CSS Selectors: class, id, attribute, and pseudo-selectors
- Box Model mastery: `margin`, `padding`
- Font and their styling
- Display property

**Reflections:**  
Today was all about making web pages look good, using different styling fonts and propeties and witnessing the changes happening, seeing it come to life was truly rewarding

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

---

### 📅 Day 4 – Café Menu: Responsive and Ready to Serve & The Mystic Ember Tavern

**Progress:**
- ✅ Completed Module 2 'Cafe Menu' with 91 lessons on freeCodeCamp!
- 🏆 Built and styled a custom tavern menu as a side quest

**New Concepts Learned:**
- External stylesheet linking (`styles.css`)  
- `background-image` and layout centering (`width`, `margin`)  
- Class-based styling (`.menu`, `.item`, `.flavor`, `.price`)  
- `display: inline-block` for side-by-side layout  
- Responsive setup via `<meta viewport>`

**Side Quest – The Mystic Ember Tavern Menu:**
🍻 Designed a fantasy-themed menu for "The Mystic Ember Tavern", featuring magical elixirs and delicious foods  
🔗 [Live Preview on GitHub Pages](https://seuhen.github.io/WebDevLog/Day%204/Tavern%20Menu%20(Side%20Quest)/tavern_menu.html)

**Menu Features:**
- Themed color palette with warm, ember-inspired tones
- Menu items grouped for elixirs and foods
- Decorative header and custom font

**Reflections:**
Today I finally completed the lessons and the menu came to shape. I also made a custom menu for a fantasy tavern in the same way.

**Snippet:**
```html
<article class="item">
      <p class="flavor">French Vanilla</p><p class="price">3.00</p>
    </article>
    <article class="item">
      <p class="flavor">Caramel Macchiato</p><p class="price">3.75</p>
    </article>
    <article class="item">
      <p class="flavor">Pumpkin Spice</p><p class="price">3.50</p>
</article>
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
```

---

### 📅 Day 5 – CSS Color Markers: Painting the Web!

**Progress:**
- ✅ Completed all lessons of Module 3, "CSS Color Markers", on freeCodeCamp!

---

**New Concepts Learned:**
- Applying colors with named values, hex codes, rgb(), and hsl()
- Setting background and text colors
- Using opacity and alpha channels for transparency
- Creating gradients for backgrounds and decorative effects
- Styling marker shapes with `border-radius` and shadows

---

**Reflections:**  
Today was vibrant! I explored how to bring color to web pages and make elements pop using different color systems in CSS. Playing with gradients and transparency made the designs feel more dynamic and modern. The color marker project was a fun, creative way to solidify these concepts.

---

**Snippet:**
```html
<h1>CSS Color Markers</h1>
    <div class="container">
      <div class="marker red">
        <div class="cap"></div>
        <div class="sleeve"></div>
      </div>
      <div class="marker green">
        <div class="cap"></div>
        <div class="sleeve"></div>
      </div>
      <div class="marker blue">
        <div class="cap"></div>
        <div class="sleeve"></div>
      </div>
    </div>
```
```css
.red {
  background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
  box-shadow: 0 0 20px 0 rgba(83, 14, 14, 0.8);
}

.green {
  background: linear-gradient(#55680D, #71F53E, #116C31);
  box-shadow: 0 0 20px 0 #3B7E20CC;
}

.blue {
  background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%), hsl(240, 56%, 42%));
  box-shadow: 0 0 20px 0 hsla(223, 59%, 31%, 0.8);
}
```

---
