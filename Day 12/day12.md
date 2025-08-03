### 📅 Day 12 – Typography with a Nutrition Label

**Progress:**  
- ✅ Completed 30 of 68 lessons of the freeCodeCamp Typography module.  
- ✅ Built a nutrition label layout using semantic HTML and CSS.  
- ✅ Applied typographic styles including `font-size`, `font-weight`, and `font-style`.  
- ✅ Used spacing properties: `line-height`, `letter-spacing`, and `word-spacing`.

**New Concepts Learned:**  
- Using `font-size`, `font-weight`, and `font-style` to control text appearance.  
- Adjusting `line-height`, `letter-spacing`, and `word-spacing` for readability.  
- Applying `em` and `px` units for scalable and precise sizing.  
- Structuring content semantically with `<section>`, `<h1>`, `<p>`, and `<ul>`.

**Reflections:**  
Typography revealed its depth today; small tweaks to spacing and weight transformed the layout’s tone. The nutrition label exercise grounded me in real-world formatting challenges, and I’m feeling more comfortable with `em` units and semantic structures.

**Snippet:**  
```html
<header>
  <h1 class="bold">Nutrition Facts</h1>
  <div class="divider"></div>
  <p>8 servings per container</p>
  <p class="bold">Serving size <span>2/3 cup (55g)</span></p>
</header>
```
```css
html {
  font-size: 16px;
}

body {
  font-family: 'Open Sans', sans-serif;
}

header h1 {
  text-align: center;
  margin: -4px 0;
  letter-spacing: 0.15px
}
```
