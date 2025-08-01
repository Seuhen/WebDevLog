### 📅 Day 10 – Rothko Painting: Module Complete & Advanced CSS Effects

**Progress:**
- ✅ Finished all remaining lessons of Module 6 ("Rothko Painting") on freeCodeCamp!
- 🟧 Enhanced the Rothko-inspired art: added more color blocks, blur, rotation, and shadow effects
- 🟧 Used advanced CSS to mimic the softness and layering of real paintings

**New Concepts Learned:**
- Applying `filter: blur()` for soft, painted edges
- Using `box-shadow` and `border-radius` for depth and realism
- Combining multiple colored divs for a layered composition
- Using `transform: rotate()` for natural, non-uniform shapes
- Fine-tuning layout with percentage widths and responsive units

**Reflections:**  
Wrapping up this module, I got to experiment with CSS filters, shadows, and transformations to make code-based art more expressive and realistic. It was rewarding to see several abstract blocks come together to evoke a real painting—just with HTML and CSS!

**Snippet:**
```html
<div class="frame">
  <div class="canvas">
    <div class="one"></div>
    <div class="two"></div>
    <div class="three"></div>
  </div>
</div>
```
```css
.canvas {
  width: 500px;
  height: 600px;
  background-color: #4d0f00;
  overflow: hidden;
  filter: blur(2px);
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
  box-shadow: 0 0 3px 3px #efb762;
  border-radius: 9px;
  transform: rotate(-0.6deg);
  filter: blur(1px);
}
.two {
  width: 475px;
  height: 200px;
  background-color: #8f0401;
  margin: 0 auto 20px;
  box-shadow: 0 0 3px 3px #8f0401;
  border-radius: 8px 10px;
  transform: rotate(0.4deg);
  filter: blur(1px);
}
.three {
  width: 91%;
  height: 28%;
  background-color: #b20403;
  margin: auto;
  filter: blur(2px);
  box-shadow: 0 0 5px 5px #b20403;
  border-radius: 30px 25px 60px 12px;
  transform: rotate(-0.2deg);
}
```
