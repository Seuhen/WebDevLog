### 📅 Day 9 – Rothko-Inspired Painting

**Progress:**
- ✅ Completed up to Lesson 22 of 45 total of Module 6 ("Rothko Painting") on freeCodeCamp
- 🎨 Created a Rothko-inspired abstract painting using HTML and CSS
- Set up a `.canvas` and `.frame` to emulate a classic art presentation
- Added a single colored block for the painting focus

**New Concepts Learned:**
- Using divs, width, height, and background colors for compositional art
- Adding thick borders, padding, and margin for a classic frame effect
- Exploring `overflow: hidden` and block alignment with margin auto

**Reflections:**  
Today I combined coding and creativity, using only HTML and CSS to recreate a Rothko-style painting. Even with basic layout and color, code can produce visually striking results. Looking forward to more CSS art experiments as the module continues.

**Snippet:**
```html
<div class="frame">
  <div class="canvas">
    <div class="one"></div>
  </div>
</div>
```
```css
.canvas {
  width: 500px;
  height: 600px;
  background-color: #4d0f00;
  overflow: hidden;
}
.frame {
  border: 50px solid black;
  width: 500px;
  padding: 50px;
  margin: 20px auto;
}
.one {
  width: 425px;
  height: 150px;
  background-color: #efb762;
  margin: 20px auto;
}
