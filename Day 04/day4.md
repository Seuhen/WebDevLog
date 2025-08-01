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
