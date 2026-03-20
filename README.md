# Nano Banana Technologies - Landing Page

**Muhammad Haris Khan** 

**23I-5558** 

**Semester 6** 

**Webprogramming for business**

---

## 🍌 Project Overview
This project is the primary assignment for the **Web Programming (CS3010)** course. It features a high-fidelity landing page for "Nano Banana," a fictional biotechnology startup specializing in microscopic, banana-based nanobots designed for targeted medical delivery systems.

## 🛠️ Technical Implementation

### 📐 Advanced CSS Grid Layout
The core architecture is built using **Pure CSS Grid** without the use of any preprocessors (Sass/LESS).
* **Grid Structure**: Implements a standard grid with a minimum of 4 columns and 5 rows.
* **Asymmetrical Design**: Features a non-traditional layout where specific items span 3 columns on the left while the right side contains smaller stacked items.
* **Overlapping Elements**: Utilizes the `z-index` property to create a 20-30% overlap between key grid items, providing visual depth.
* **Irregular Geometries**: Includes a diagonal hero section and a footer designed with an angled top edge to break the standard rectangular grid convention.

### 📝 Flexbox-Powered Appointment Form
The consultation booking form is built using **CSS Flexbox** for precise internal component alignment.
* **Vertical/Horizontal Stacking**: Uses `flex-direction: column` for general layout and `row` for side-by-side fields like Name and Date/Time.
* **Client-Side Validation**: Employs strict HTML5 validation for email formats, phone number patterns, and specific business hours.
* **Accessibility**: Fully semantic structure with proper labels and keyboard navigation support.

### 🎨 CSS Animations & Interactivity
Three distinct CSS animations are integrated into the user interface:
1. **Nano Banana Logo**: A continuous floating animation using `@keyframes` that makes the logo bob up and down.
2. **Feature Cards**: A smooth 0.3s transition on hover that scales the cards to 1.05x and adds a box-shadow.
3. **Form Inputs**: A transform animation on focus that applies a subtle scale effect and a glowing border.

### 📱 Responsive Design & Mobile Collapse
The website is fully responsive across all major device breakpoints using standard Media Queries:
* **Desktop (1200px+)**: The full asymmetrical grid layout.
* **Tablet (992px - 768px)**: Optimized column spans and scaled-down spacing.
* **Mobile (480px)**: **CRITICAL COLLAPSE** – The entire grid transforms into a single-column `1fr` layout. All overlapping elements are neutralized and stacked vertically in document order.

## 📂 Project Structure
* `index.html`: Semantic HTML5 document structure.
* `styles.css`: External stylesheet containing all layout and animation rules.
* `wireframe.jpg`: Photo of the mandatory hand-drawn physical wireframe.
* `images/`: Directory containing the logo and nanobot illustrations.

## 👨‍🏫 Course Information
* **Instructor**: Arsalan Khan
* **Institution**: FAST National University of Computer and Emerging Sciences, Islamabad Campus
* **Academic Year**: 2026
