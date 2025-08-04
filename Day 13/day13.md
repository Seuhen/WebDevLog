### 📅 Day 13 – Typography Module Completion

**Progress:**  
✅ Finished the remaining lessons of the Typography module  
✅ Completed the nutrition label project with semantic HTML and accessible structure  
✅ Reviewed and reinforced all prior concepts from the module

**Reflections 🧠**  
This final stretch brought everything together. The nutrition label project was a satisfying test of structure, styling, and clarity—like assembling a layout puzzle with all the right pieces. I now feel confident applying these principles to real-world interfaces, and this module gave me a solid foundation for accessible, well-structured design.

**Dev Mood 💬**  
Focused, accomplished, and ready to build on this momentum

**Snippet 🔍**  
```html
<div class="daily-value small-text">
  <p class="bold right no-divider">% Daily Value *</p>
  <div class="divider"></div>
  <p><span><span class="bold">Total Fat</span> 8g</span> <span class="bold">10%</span></p>
  <p class="indent no-divider">Saturated Fat 1g <span class="bold">5%</span></p>
  <div class="divider"></div>
  <p class="indent no-divider"><span><i>Trans</i> Fat 0g</span></p>
  <div class="divider"></div>
  <p><span><span class="bold">Cholesterol</span> 0mg</span> <span class="bold">0%</span></p>
  <p><span><span class="bold">Sodium</span> 160mg</span> <span class="bold">7%</span></p>
  <p><span><span class="bold">Total Carbohydrate</span> 37g</span> <span class="bold">13%</span></p>
  <p class="indent no-divider">Dietary Fiber 4g</p>
  <div class="divider"></div>
  <p class="indent no-divider">Total Sugars 12g</p>
  <div class="divider double-indent"></div>
  <p class="double-indent no-divider">Includes 10g Added Sugars <span class="bold">20%</span></p>
  <div class="divider"></div>
  <p class="no-divider"><span><span class="bold">Protein</span> 3g</span></p>
  <div class="divider large"></div>
  <p>Vitamin D 2mcg <span>10%</span></p>
  <p>Calcium 260mg <span>20%</span></p>
  <p>Iron 8mg <span>45%</span></p>
  <p class="no-divider">Potassium 235mg <span>6%</span></p>
</div>
```
```css
.calories-info span {
  margin: -7px -2px;
  font-size: 2.4em;
  font-weight: 700;
}

.right {
  justify-content: flex-end;
}

.indent {
  margin-left: 1em;
}

.double-indent {
  margin-left: 2em;
}

.daily-value p:not(.no-divider) {
  border-bottom: 1px solid #888989;
}

.note {
  font-size: 0.6rem;
  margin: 5px 0;
  padding: 0 8px;
  text-indent: -8px;
}
```
