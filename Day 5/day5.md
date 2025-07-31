### 📅 Day 5 – CSS Color Markers: Painting the Web!

**Progress:**
- ✅ Completed all lessons of Module 3, "CSS Color Markers", on freeCodeCamp!

**New Concepts Learned:**
- Applying colors with named values, hex codes, rgb(), and hsl()
- Setting background and text colors
- Using opacity and alpha channels for transparency
- Creating gradients for backgrounds and decorative effects
- Styling marker shapes with `border-radius` and shadows

**Reflections:**  
Today was vibrant! I explored how to bring color to web pages and make elements pop using different color systems in CSS. Playing with gradients and transparency made the designs feel more dynamic and fun.

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
