# 🚀 Frontend Challenge

## 🎯 Purpose
This challenge is designed to test your **frontend development skills** within the **JavaScript ecosystem**, as well as your ability to **think critically**, **explore alternatives**, **design**, **build**, **test**, and **document** your work effectively.

---

## 🎥 Demo Output
A few key aspects to observe in the demo video:

- The app features a **canvas with three interactive layers**, each **zoomable** and **panable**.
- When you click (zoom in) on a node, the app **animates smoothly** - the current layer fades outward toward the browser edges ✨, while the next layer emerges from the center of the canvas.  
  (The same transition happens in reverse when zooming out.)
- The **background color** of the next layer is **inherited** from the node’s color where the zoom-in originated 🎨 (and vice versa for zoom-out).
- This experience is **inspired by Google Maps**, where *countries → cities → streets* are rendered across multiple layers with smooth transitions and intuitive zooming behavior.

<video width="100%" autoplay muted loop>
  <source src="assets/multi-layered-demo.mov" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## 🧩 Your Task
Design a **web application** that takes a configuration as input and **dynamically renders** an interactive, performant visualization similar to (or better than) the demo above.

### ⚙️ Input
You are free to choose the data format — e.g. **JSON**, **XML**, **CSV**, **Binary**, etc. — as long as it effectively captures:

- Canvas style attributes  
- Layer definitions  
- Node content and style attributes  
- Parent → Child → Grandchild relationships between nodes  
- Any other configuration you find necessary  

---

## 👤 Functional Requirements

Your web app should allow a user to perform the following interactions:

### **US-001: Navigate Between Layers**
Users can move between layers (top-down) by zooming **in** or **out** on nodes using:

- **Zoom In:**
  - Mouse scroll-up over a specific node
  - Left-click on a specific node
- **Zoom Out:**
  - Mouse scroll-down over a specific node
  - Right-click anywhere on the current layer to go back to the previous layer

---

### **US-002: Home Button 🏠**
Clicking the **Home** icon should return the user to the **top-level layer** (e.g., “Water Cycle” in the demo).

---

### **US-003: Layer Navigation via Bubbles 🔵**
Clicking on any **bubble** in the vertical UI (below the Home button, where each bubble represents a visited layer) should take the user directly to that specific layer.

---

## 📊 Points & Weightage

| Criteria | Description | Weight |
|-----------|--------------|--------|
| **✨ Animation** | Smooth and visually appealing zoom-in / zoom-out effects. The more fluid and polished your animations, the higher your score. | **40%** |
| **🧱 Maintainability** | Clean, well-structured, and self-explanatory code. Bonus points for meaningful comments and concise inline documentation. | **40%** |
| **🌐 Compatibility** | Must run on popular browsers and devices (PC, Mac, Mobile). Avoid dependency on a single environment or format. | **20%** |

---

## 📦 Deliverables

Please share a **GitHub repository** containing:

- A **README.md** with:
  - 🧭 **Overview** — Brief description of the problem  
  - 🧩 **Design** — Your architectural and UI/UX approach  
  - ⚙️ **Tech Choices** — Technologies, frameworks evaluated/chosen, and justification  
  - ✅ **Tests** — How to run and verify them  
- 💻 **Working Code** (with tests) runnable locally

---

## 🌟 Good Luck & Have Fun! 🙌
Show off your creativity, attention to detail, and ability to craft smooth, interactive experiences.  

Happy coding! 💪

