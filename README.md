# King Sukh Guest House Website Redesign

## Project ID: 78GRB6TY2D

A complete front-end redesign and re-engineering of the existing King Sukh Guest House website, focusing on a modern aesthetic, superior user experience, and full mobile responsiveness.

---

## 🚀 Project Goals

The core objectives of this redesign were to transform an outdated digital presence into a modern, conversion-focused platform:

-   **Enhanced Aesthetics:** Implement a modern, elegant, and inviting design using a curated color palette and premium typography.
-   **Full Responsiveness:** Ensure pixel-perfect display and functionality across all devices (mobile, tablet, desktop) using a Mobile-First development approach.
-   **Improved UX/UI:** Implement dynamic features like a sticky header, smooth scroll animations, a Dark Mode toggle, and clear Call-to-Action (CTA) placement to drive bookings.
-   **High Performance:** Utilize a lightweight, native technology stack (Vanilla JS, pure CSS) to ensure fast loading times and smooth transitions.

---

## 💻 Tech Stack

This project was built using a minimal, high-performance, and native front-end stack.

| Category | Technology | Rationale |
| :--- | :--- | :--- |
| **Structure** | HTML5 (Semantic) | Ensures clean, accessible, and SEO-friendly document markup. |
| **Styling** | CSS3 (Native Flexbox & Grid) | Custom, lightweight styling. Native layout modules ensure maximum performance and precise control over complex responsive layouts without framework bloat. |
| **Interactivity** | Vanilla JavaScript | High-performance dynamic features with zero external dependencies, maximizing speed and maintainability. |
| **Theming** | CSS Variables | Used for instant, maintainable theming (Light/Dark Mode). |
| **Assets** | Font Awesome, Google Fonts | Standard libraries for icons and custom typography (`Playfair Display` & `Poppins`). |

---

## ✨ Key Features Implemented

The redesign incorporates advanced front-end techniques to deliver a premium user experience:

-   **Dark Mode Toggle:** A user-preference feature implemented using CSS Variables and `localStorage` for theme persistence across sessions.
-   **Conversion-Focused CTAs:** A Sticky Header with a persistent "Book Now" button, a Floating WhatsApp Button, and a Bottom Promo Bar ensure booking visibility on all screens.
-   **Scroll Animations (Intersection Observer):** Content sections are animated into view using the **Intersection Observer API** for performance-optimized, smooth "fade-in-up" entrance effects.
-   **Image Lightbox Gallery:** A custom, fully responsive modal implementation that displays high-resolution gallery images and prevents background scrolling.
-   **Sticky Header Logic:** Uses JavaScript to apply a "shrink-on-scroll" effect, reducing the header size to maximize content visibility after the user begins scrolling.
-   **Mobile-First Navigation:** Implements a standard hamburger menu that expands into a full-screen overlay for easy navigation on small devices.

---

## 📁 Project Structure
The repository follows a clean and logical file structure:
```bash
kingsukh-guesthouse-redesign/
├── assets/
│   ├── images/         # All high-resolution images (Hero, Rooms, Gallery)
│   └── logos/          # Logo files and favicon
├── index.html          # Main application structure, content, and JavaScript logic
├── styles.css          # All custom CSS, variables, theming, and media queries
└── README.md           # Project documentation and guide (This file)
 
``` 
---

## 🛠 Getting Started (Local Setup)

To run this project locally, follow these simple steps:

1.  **Clone the Repository:**
    ```bash
    git clone [YOUR_REPO_URL_HERE]
    ```

2.  **Navigate to the Project Directory:**
    ```bash
    cd kingsukh-redesign
    ```

3.  **Open in Browser:**
    Open the `index.html` file directly in your web browser. This project requires no build tools or server environment, as it is pure static HTML/CSS/JS.

    > *You can use the "Go Live" extension in VS Code for a better local development experience.*

---
## Live Project Demonstration 
To provide immediate evidence of the project's quality and functionality, the following demonstration highlights key dynamic features implemented in the redesign:
-   **Responsiveness:** Viewing the layout fluidly across screen sizes. 
-   **Dynamic Header:** The "shrink-on-scroll" effect of the sticky navigation. 
-   **Interactivity:** Toggling the Dark Mode and triggering Scroll Animations.
*   **Dark Mode:** [Click Here](https://drive.google.com/file/d/1UUQbDcX6SzI94sccatpcDS_HYK6tSUz0/view?usp=sharing)
*   **Light Mode:** [Click Here](https://drive.google.com/file/d/1dbPPWRQdrBTTNWVDIKfLMAugU07jggpt/view?usp=sharing)
 
---
## 💡 Future Enhancements (Roadmap)

The following features are recommended for future development:

-   **Backend Integration:** Implement server-side logic (e.g., using Node.js or a serverless function) to handle submissions from the Contact Form.
-   **Image Optimization:** Convert all large images to the WebP format and utilize native `loading="lazy"` attributes for enhanced performance metrics.
-   **Advanced Booking Integration:** Connect the "Book Now" buttons to a real-time third-party booking management system API.
-   **Accessibility (A11Y) Audit:** Conduct a full review to ensure WCAG compliance, including ARIA labels and enhanced keyboard navigation.

---

*Developed for the InnoByte Services Internship Program.*
&copy; 2024 King Sukh Guest House Redesign
