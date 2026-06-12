#  Flame & Fork Bistro

Welcome to the official repository for **Flame & Fork Bistro**—a premium, modern, and fully responsive restaurant website designed to deliver an elegant online dining experience. From a sleek multi-column menu grid to an interactive infinite-loop gallery, this landing page blends high-end aesthetics with seamless performance.

##  Features

###  Premium Menu Section
*   **Compact & Grid-Aligned:** Replaced large, overwhelming text blocks with a sleek, space-efficient CSS Grid layout.
*   **Uniform Media Aspect Ratio:** Image boundaries are strictly controlled (`object-fit: cover`) preventing visual distortion or misalignment.
*   **Interactive Hover Effects:** Cards gracefully lift (`translateY`) and cast a subtle depth shadow when hovered over.
*   **Flexbox Alignment:** The "Order Now" action buttons dynamically snap to the absolute bottom of their rows regardless of variations in description text length.

###  Infinite Auto-Scrolling Gallery
*   **Seamless Infinite Loop:** Utilizes a pure CSS-duplicated track illusion (`translateX(-50%)`) to create a smooth, never-ending right-to-left marquee without any stutters or sudden page jumps.
*   **Zero-JS Performance:** Driven completely by hardware-accelerated CSS keyframes for butter-smooth rendering on both desktops and low-tier mobile devices.
*   **Interactive Control:** The animation automatically pauses when a user hovers over an image, letting them focus on a dish, coupled with a gentle magnification scale effect (`scale(1.03)`).

###  Table Reservation System
*   A fully styled reservation interface allowing customers to book a dining slot cleanly by configuring guest count, timings, and custom food requests.

---

##  Tech Stack Used

*   **HTML5:** Structured semantic layout defining clean sections (`<section>`, `<nav>`, `<footer>`).
*   **CSS3:** Custom properties, CSS Flexbox, CSS Grid, and custom keyframe animations (`@keyframes`).

---

##  Project Structure

```text
├── index.html          # Main landing page markup 
├── css/
│   └── style.css       # Core stylesheet containing Grid, Flexbox & Infinite loop rules

```

---

##  How to Run Locally

1. **Clone the repository:**

```bash
   git clone https://github.com/dk132006/restaurant-website.git

```

2. **Navigate to the directory:**

```bash
   cd restaurant-website
```

3. **Open the file:**
Launch `index.html` directly in any browser, or run it via VS Code's **Live Server** extension for real-time adjustments.

---



© 2026 Flame & Fork Bistro | Crafted with Passion.

```

```
