🧑‍💻 Lab Assignment 3: Responsive Personal Portfolio Website (CSS Advanced)
Project Description

This project is a one-page personal portfolio website for Vaishnavi, built to demonstrate proficiency in advanced CSS layout techniques and responsive design principles. The primary objective was to upgrade a traditional layout using modern CSS features, ensuring the entire site is fluid and adapts seamlessly across different device sizes, while strictly following the specified CSS methods.

🚀 Key Features and Technologies Used

The portfolio strictly implements all required advanced CSS techniques:

1. Layout Management (Flexbox & CSS Grid)

Flexbox:
Used for the header navigation, the two-column layout of the Hero section (text and image), the Projects section card arrangement, and structuring the Contact Form elements.

CSS Grid:
Used exclusively for the Skills section to create a structured four-column card layout on desktop and tablet views.

2. Responsive Design (Media Queries & Relative Units)

Mobile-First Approach:
Base styles are optimized for mobile devices, with elements stacked vertically.

Media Query:
A single media query at the 768px breakpoint transitions the layout into a side-by-side arrangement (Hero, Projects, and Skills shifting from 1 to multiple columns).

Relative Units:

rem for font sizing

% for padding and margins

vw (viewport width) for profile image sizing
These units ensure consistent scaling and responsiveness across devices.

3. Animations & Effects

Keyframe Animation:
An animated text effect using @keyframes colorChange is applied to the main title “Full Stack Developer”, creating a smooth color-changing transition.

Transitions & Transforms:

CSS transitions (transition) and transforms (transform) add smooth hover effects to navigation links, buttons, and section cards.

Skill cards feature a lift-up hover effect using transform: translateY() along with a multi-layered shadow that simulates a glowing linear gradient using the theme colors #3b5998 and #e94e77.

🖥️ Steps to View Responsive Behavior

Clone the Repository:
Download or clone the project files (index.html and style.css).

Open in Browser:
Open the index.html file in any modern web browser.

Test Breakpoints:

Mobile View (Viewport < 768px):
The Hero section displays text stacked above the image. Skills and Projects cards appear in a single column.

Desktop/Tablet View (Viewport ≥ 768px):
The layout shifts to a desktop design where the Hero section appears side-by-side, Skills cards display in a four-column grid, and Projects cards appear in a two-column Flexbox layout.
