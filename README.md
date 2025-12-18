🧑‍💻 Lab Assignment 3: Responsive Personal Portfolio Website (CSS Advanced)
Project Description
This project is a one-page personal portfolio website for Chirag, built to demonstrate proficiency in advanced CSS layout techniques and responsive design principles. The primary objective was to upgrade the traditional layout using modern CSS features, ensuring the entire site is fluid and adapts seamlessly across different device sizes, and strictly adhering to the specified CSS methods.

🚀 Key Features and Technologies Used
The portfolio strictly implements all required advanced CSS techniques:

1. Layout Management (Flexbox & CSS Grid)
Flexbox: Used for the Header navigation, the two-column layout of the Hero section (text and image), the Projects section card arrangement, and structuring the Contact Form elements.
CSS Grid: Used exclusively for the Skills section to create a structured, four-column card layout on desktop and tablet views.
2. Responsive Design (Media Queries & Relative Units)
Mobile-First Approach: The base styles are optimized for mobile devices (elements stacked vertically).
Media Query: A single media query is implemented at the 768px breakpoint to transition the layout to a side-by-side arrangement (Hero, Projects, Skills changing from 1 to 4 columns).
Relative Units: rem is used for font sizing, % for padding/margins, and vw (viewport width) for the profile image sizing, ensuring consistent and scalable spacing.
3. Animations & Effects
Keyframe Animation: An animated text effect (@keyframes colorChange) is applied to the main title ("Full Stack Developer"), featuring a color-changing transition.
Transitions & Transforms:
CSS Transitions (transition) and Transforms (transform) provide smooth hover effects on navigation links, buttons, and section cards.
The Skill Cards feature a unique hover effect where they lift up (transform: translateY) and display a multi-layered shadow simulating a linear gradient glow using the theme colors (#3b5998 and #e94e77).
🖥️ Steps to View Responsive Behavior
Clone the Repository: Download or clone the project files (index.html and style.css).
Open in Browser: Open the index.html file in any modern web browser.
Test Breakpoints:
Mobile View (Viewport < 768px): The Hero section shows the text stacked above the image. Skills and Projects cards stack in a single column.
Desktop/Tablet View (Viewport ≥ 768px): The layout transitions to a desktop design: the Hero section becomes side-by-side, Skills cards display in a 4-column Grid, and Projects cards display in a 2-column Flexbox layout.
About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
CSS
58.3%
 
HTML
41.7%
Footer
© 2025 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
