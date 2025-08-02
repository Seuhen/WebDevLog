### 📅 Day 11 – Photo Gallery with CSS Flexbox

**Progress:**
- ✅ Built a responsive photo gallery using CSS flexbox.
- ✅ Implemented a flexible layout for images and styled a clean header.
- ✅ Ensured images maintain their aspect ratio with object-fit.

**New Concepts Learned:**
- Utilizing flexbox properties such as `display: flex`, `flex-wrap`, `justify-content`, and `align-items` to create responsive layouts.
- Applying CSS techniques like `object-fit`, `border-radius`, and gaps to enhance visual presentation.
- Structuring HTML and CSS to achieve a balanced, aesthetic photo gallery with minimal markup.

**Reflections:**  
Today, I focused on creating a dynamic and responsive photo gallery. Leveraging CSS flexbox made it straightforward to center the gallery and manage spacing between images. The final design is both visually appealing and functionally responsive, perfect for showcasing a series of photos.

**Snippet:**

<img src="https://cdn.freecodecamp.org/curriculum/css-photo-gallery/7.jpg" alt="white cat looking at the camera">

```css
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: sans-serif;
  background: #f5f6f7;
}

.header {
  text-align: center;
  text-transform: uppercase;
  padding: 32px;
  background-color: #0a0a23;
  color: #fff;
  border-bottom: 4px solid #fdb347;
}

.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  gap: 16px;
  max-width: 1400px;
  margin: 0 auto;
  padding: 20px 10px;
}

.gallery img {
  width: 100%;
  max-width: 350px;
  height: 300px;
  object-fit: cover;
  border-radius: 10px;
}

.gallery::after {
  content: "";
  width: 350px;
}
