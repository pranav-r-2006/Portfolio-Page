README.txt

-------------------------------------------------------------------------------
                                PORTFOLIO WEBSITE
-------------------------------------------------------------------------------

Repository: Portfolio-Page  
Author: Pranav R  
GitHub: https://github.com/pranav-r-2006  
Live Demo: https://pranav-r-2006.github.io/Portfolio-Page/  
Created using: HTML5, CSS3 (Vanilla)

-------------------------------------------------------------------------------
                                TABLE OF CONTENTS
-------------------------------------------------------------------------------

1. Introduction
2. Website Structure
3. Design Philosophy
4. Technologies Used
5. Page-by-Page Breakdown
    - Welcome Page
    - Home Page
    - Education Page
    - Projects Page
    - Skills Page
    - Contact Me Page
6. Responsiveness
7. Footer and External Links
8. Media Files
9. Future Plans
10. How to Use or Customize
11. Acknowledgements

-------------------------------------------------------------------------------
1. INTRODUCTION
-------------------------------------------------------------------------------

Welcome to my personal Portfolio Website!

This project is a fully responsive, aesthetically appealing, and interactive portfolio designed to showcase my professional background, technical skills, academic qualifications, and personal projects. The website serves as a digital resume, allowing potential employers, collaborators, or interested viewers to explore who I am as a Computer Science undergraduate.

The site is divided into six main sections, each crafted with care and attention to detail, leveraging simple but powerful HTML and CSS to bring interactivity and personality to each component.

-------------------------------------------------------------------------------
2. WEBSITE STRUCTURE
-------------------------------------------------------------------------------

The project directory contains the following:

- `index.html` – Main landing (Welcome) page
- `home.html` – Home page with navigation and introduction
- `education.html` – Academic background and achievements
- `projects.html` – Showcases selected personal projects
- `skills.html` – Highlights programming languages and soft skills
- `contact.html` – For professional contact and social outreach
- `css/` – Folder containing separate stylesheet files for each section
- `assets/` – Folder that holds videos, images, icons, etc.
- `README.txt` – This documentation file

Each section has its own unique stylesheet (e.g., `StylesHome.css`, `StylesSkills.css`), ensuring modularity and easier customization or debugging.

-------------------------------------------------------------------------------
3. DESIGN PHILOSOPHY
-------------------------------------------------------------------------------

The website's visual and structural design is based on four main principles:

1. **Simplicity with Elegance**: The use of a minimal color palette, animations, and clean fonts (Raleway) makes the site visually appealing without overloading the user.
2. **Consistency**: All sections follow a consistent visual language—typography, hover effects, transparency effects, and animation speeds are uniform throughout.
3. **Accessibility & Usability**: All text is readable across devices. Interactive elements like buttons and progress bars have intuitive hover/click behaviors.
4. **Responsiveness**: The design adapts gracefully across desktops, tablets, and smartphones.

-------------------------------------------------------------------------------
4. TECHNOLOGIES USED
-------------------------------------------------------------------------------

- **HTML5**: Core structure of all pages.
- **CSS3**: Handles all design elements, transitions, animations, and responsiveness.
- **Media Queries**: For ensuring device-specific responsiveness.
- **Google Fonts (Raleway)**: For a modern, clean font aesthetic.
- **Font Awesome / SVG Icons**: For social media links and navigation cues.


Note: This project does not use JavaScript intentionally, to keep everything fast and lightweight.

-------------------------------------------------------------------------------
5. PAGE-BY-PAGE BREAKDOWN
-------------------------------------------------------------------------------

-------------------------
Welcome Page (index.html)
-------------------------


- A centrally placed typing animation welcomes the user with the text:
  “Welcome to my Portfolio”.
- Once the animation finishes, the text transforms into a glowing, enlarging button.
- On hover, this button reacts visually and links the user to the Home Page.
- Uses Raleway font and a focused layout to engage users immediately.

--------------------
Home Page (index.html)
--------------------

- Retains the same video background and Poppins font for design consistency.
- A **Navigation Panel** drops down slowly on load and contains buttons for:
  - Education
  - Projects
  - Skills
  - Contact Me
- Each button has a glow and enlarge hover effect.
- The **About Me Section** is displayed in a black translucent box with rounded corners.
  - The section fades in on load.
  - It provides a short narrative about who I am, my academic focus, and goals.
- The **Footer** includes:
  - Physical address placeholder
  - Copyright:
    “© Pranav R | Designed with care”
  - Social media buttons for:
    - GitHub: [https://github.com/pranav-r-2006](https://github.com/pranav-r-2006)
    - LinkedIn: [https://www.linkedin.com/in/pranav-r-76292031a](https://www.linkedin.com/in/pranav-r-76292031a)
    - Twitter X (icon only)
    - Instagram (icon only)

------------------------
Education Page (education.html)
------------------------

- Presents academic history in a structured tabular format.
- Displays:
  - School Name
  - Board (e.g., CBSE/State)
  - Year of Passing
  - Grades/Percentage
- Tables are styled with subtle hover effects and border spacing.
- A floating footer appears on hover, maintaining visual consistency with the Home page.

-----------------------
Projects Page (projects.html)
-----------------------

- Highlights selected projects (such as Helping Hands, Smart Street Light, etc.).
- Each project is displayed in a card format (planned or implemented).
- Each card contains:
  - Project Title
  - Short Description
  - Technologies Used
  - Status (Completed / Ongoing)
- Optionally expandable cards may be added in future with GitHub links.

--------------------
Skills Page (skills.html)
--------------------

- Features animated progress bars to show proficiency in:
  - HTML
  - CSS
  - Python
  - C
  - C++
  - Git & GitHub
- Bars are color-coded and fill on page load.
- Finishes with a “Closing Note” section:
  - Emphasizes continuous learning and curiosity.
- Floating footer included, same as previous pages.

-------------------------
Contact Me Page (contact.html)
-------------------------

- A contact form or email contact section is planned.
- Placeholder for now, but includes floating footer and icons for social reach.
- Visitors are encouraged to connect through LinkedIn or GitHub.

-------------------------------------------------------------------------------
6. RESPONSIVENESS
-------------------------------------------------------------------------------

- Designed with mobile-first approach.
- All layouts, fonts, containers, and animations adjust based on screen size.
- Media queries used to handle:
  - Font resizing
  - Button layout shifts
  - Container stacking on small screens
- Verified on:
  - Desktop (Chrome, Firefox)
  - Tablet (Android)
  - Mobile (Chrome on Android)

-------------------------------------------------------------------------------
7. FOOTER AND EXTERNAL LINKS
-------------------------------------------------------------------------------

The footer is common across most sections and includes:

- © Pranav R | Designed with care
- Contact Address (can be customized)
- Social Media Icons:
  - GitHub: [https://github.com/pranav-r-2006](https://github.com/pranav-r-2006)
  - LinkedIn: [https://www.linkedin.com/in/pranav-r-76292031a](https://www.linkedin.com/in/pranav-r-76292031a)
  - Twitter and Instagram icons (Links to be added)

These links open in new tabs and are safe for navigation.

-------------------------------------------------------------------------------
8. MEDIA FILES
-------------------------------------------------------------------------------

- `Background1.mp4`: The primary background video file used across pages.
  - Muted and looped
  - Adds dynamic motion to the otherwise static layout
  - Chosen to be light-weight and subtle

More media (project images, icons, etc.) may be added in the assets folder in future.

-------------------------------------------------------------------------------
9. FUTURE PLANS
-------------------------------------------------------------------------------

- Add JavaScript interactivity (form validation, scroll-based animations)
- Add contact form with back-end email functionality
- Include blog section for writing on tech, college life, and mini-projects
- Improve accessibility with ARIA labels and semantic HTML
- Optimize load times for mobile users
- Integrate feedback section or testimonials
- Develop a light/dark theme toggle

-------------------------------------------------------------------------------
10. HOW TO USE OR CUSTOMIZE
-------------------------------------------------------------------------------

If you'd like to use this portfolio as a template:

1. Fork or Clone the Repository.
2. Replace text inside the HTML files with your own info.
3. Replace the `Background1.mp4` video file with your own.
4. Tweak styles in the `css/` folder. Each page has its own `.css` file.
5. Update social media links in the footers.
6. Host on GitHub Pages:
    - Push your changes
    - Go to repository > Settings > Pages
    - Select root directory and `/ (index.html)`
    - Wait a few minutes for deployment

-------------------------------------------------------------------------------
11. ACKNOWLEDGEMENTS
-------------------------------------------------------------------------------

- Fonts provided by Google Fonts (Poppins)
- Icons inspired by Font Awesome and SVG icon libraries
- Animation inspiration from CodePen and CSS Tricks
- Thanks to the open-source community and platforms like W3Schools and MDN for references
- Special thanks to ChatGPT for assisting in design, animation logic, and consistent styling

-------------------------------------------------------------------------------

Thank you for checking out my portfolio!

– Pranav R
