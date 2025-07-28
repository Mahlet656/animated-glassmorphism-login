## 🎯 Project Objective

This challenge is about **realism in animation**. Your task is to bring natural motion (like wind, gravity, or free fall) into the project using CSS animations. The layout includes a base animation for inspiration — feel free to get creative!

> ✨ **Goal:** Add a smooth, realistic animation (e.g., falling leaves 🍃), leveraging `transform` to simulate real-world physics.

---

## 📦 What's Inside

- A fully functional glassmorphic login page
- Base structure for animation (`<div class="leaves">`)
- Predefined CSS with comments for easy customization
- A reference image: girl on a bike, already animated
- This README file as your complete `transform` reference

---

## 🧠 CSS `transform` – The Core Engine of Motion

The `transform` property in CSS allows you to visually manipulate elements by moving, rotating, scaling, or skewing them.

### 🔁 `translate()` – Movement in Space
Moves elements without disturbing surrounding layout.

| Syntax            | Description                        |
|-------------------|------------------------------------|
| `translateX(x)`   | Moves element left/right           |
| `translateY(y)`   | Moves element up/down              |
| `translate3d(x,y,z)` | Moves in 3D space for smooth performance |

**💡 Example in Project:**  
Used to animate the **girl on a bike** moving across the screen.

---

### 🔍 `scale()` – Resizing Elements
Stretches or shrinks elements.

| Syntax         | Description                        |
|----------------|------------------------------------|
| `scaleX(val)`  | Horizontal scaling                 |
| `scaleY(val)`  | Vertical scaling                   |
| `scale(x, y)`  | Uniform or independent scaling     |

**💡 Example in Project:**  
`scaleX(-1)` flips the **girl image** to face her direction of travel.

---

### 🔄 `rotate()` – Rotating Elements
Applies rotation on 2D or 3D axes.

| Syntax           | Description                                |
|------------------|--------------------------------------------|
| `rotate(deg)`     | 2D rotation (around Z-axis)                |
| `rotateX(deg)`    | 3D rotation around X-axis                  |
| `rotateY(deg)`    | 3D rotation around Y-axis                  |

**💡 Example in Project:**  
Falling **leaves rotate** while descending for a tumbling effect.

---

### 💫 `skew()` – Distortion by Angles
Tilts the shape of an element.

| Syntax        | Description                    |
|---------------|--------------------------------|
| `skewX(deg)`  | Tilts along X-axis             |
| `skewY(deg)`  | Tilts along Y-axis             |

---

## ⚙️ Related Properties for Better Control

### 🎯 `transform-origin`
Defines the pivot point for transformations.

| Syntax                       | Effect                           |
|------------------------------|----------------------------------|
| `transform-origin: x y;`     | Sets custom anchor point         |
| `transform-origin: top left;` | Rotates from top-left instead of center |

### 🧱 `transform-style`
Sets 3D rendering of child elements.

| Value          | Description                                |
|----------------|--------------------------------------------|
| `flat` (default)| Flattens children in 2D                   |
| `preserve-3d`   | Allows children to exist in 3D space       |
