### 1.0 INTRODUCTION

This document is a comprehensive guide that provides insights into the planning, development, and design of my personal portfolio website. In the digital age, a portfolio website has become an indispensable tool for individuals across various professions and creative fields. It's a dynamic and immersive platform where one can present their best work, share their story, and connect with a global audience. Portfolio websites help create a first impression online as it is like a virtual business card. A well curated portfolio offers concrete evidence of one’s abilities and provide examples of what one can achieve. It is a great way to establish a personal brand and define one’s unique style and approach.

### 1.1 PROBLEM STATEMENT

In a rapidly evolving digital landscape, the need to establish a compelling online presence is more critical than ever. As a Computer Science student, I face the challenge of effectively showcasing my diverse talents, skills, and achievements in a dynamic and engaging manner. The existing online platforms and profiles are scattered, often lack a cohesive narrative, and do not fully reflect my personal brand. To address this issue, I aim to create a personalized portfolio website that unifies my body of work, highlights my unique identity, and provides a seamless and informative experience for visitors. This project aims to not only serve as a central hub for my accomplishments but also enhance my online visibility and professional opportunities in a competitive digital landscape.

### 1.2 OBJECTIVES

**Create an Attractive Portfolio**: The primary objective is to create an appealing and visually engaging portfolio website that effectively showcases skills, projects and personality.

**Responsive Design**: Ensure that the website is responsive and looks good on various screen sizes and devices, making it accessible to a wide audience.

**Effective Navigation**: Implement a user-friendly navigation menu that allows visitors to easily move between different sections of your portfolio.

**Branding**: Establish a clear personal brand by using consistent colors, fonts, and design elements throughout the website.

**Highlight Education**: Present educational background in an organized and visually appealing manner, showcasing your qualifications and academic achievements.

**Skills Display**: Create a section for displaying your technical and professional skills. Use progress bars or other visual elements to represent your proficiency in each skill.

**Project Showcase**: Feature your projects with detailed descriptions, images, and links to source code, enabling visitors to explore your work.

**Experience**: Highlight work experience, including internships and volunteer activities, by providing descriptions and related certificates.

**About Me**: Include an "About Me" section that provides a brief biography, interests and what drives me offering a glimpse into your personality.

**Contact Form**: Offer a functional contact form that allows visitors to get in touch with me. Ensure the form collects essential information, such as name, email, subject and message.

**Social Media Integration:** Include links to LinkedIn and GitHub profiles to encourage networking and showcase your professional presence.

**Animations**: Add subtle animations to create an interactive and engaging user experience without overwhelming the design.

**Proper Documentation**: Maintain well-organized and commented code for easier maintenance and collaboration.

**Continuous Improvement:** Plan for future updates and improvements to keep your portfolio fresh and up to date with your latest work and experiences.

### 1.3 METHODOLOGY

The methodology employed in this project represents a modern and well-organized approach to web development. It begins with a structured HTML document featuring semantic elements, ensuring proper readability and accessibility. The utilization of external CSS files, such as Bootstrap and custom styles, enables consistent and responsive design across various devices. Responsive design principles are meticulously applied, guaranteeing adaptability to different screen sizes. The webpage incorporates a smooth navigation system with animations to enhance user experience. It includes a contact form for visitors to interact, while external links to social media profiles add credibility. The code is enriched with comments and formatting for maintainability, and JavaScript is employed for smooth scrolling and form submissions. This methodology prioritizes accessibility and a professional presentation of the creator's portfolio, making it an example of contemporary web development practices.

### 1.4 EXPECTED OUTCOMES

**Navbar:** A fixed-top navigation bar will appear, with the website logo (profile picture) on the left. The navigation bar will include links to various sections of the page. When the user clicks on these links, it will smoothly scroll to the respective sections on the page.

**Content Section:** The webpage consists of several sections, each with unique content:

Home: A welcome message with name and a brief introduction, accompanied by a "Explore My Work" button and a "Download CV" link.

Qualification: Information about the user's educational qualifications, including details about their college and school.

Skills: A section showcasing the user's technical and professional skills using animated progress bars.

Projects: Presentation of various projects, each with an image, title, description, and a "Source Code" link.

Experience: Details about the user's work and volunteer experiences, each with icons, position titles, associated companies, and tenure.

About: A section where the user describes their life motto, interests, and hobbies.

Contact: A contact form allowing visitors to send messages, which is expected to be submitted to a Google Apps Script when filled out and submitted.

**Footer**: A footer section at the bottom with social media icons (LinkedIn and GitHub links).

**Responsive Design**: The webpage is expected to be responsive, adjusting its layout and content to different screen sizes and devices for a better user experience.

**Animations**: Animations are added to elements using the "data-aos" attribute, providing a smoother user experience as users scroll down the page.

**Script Execution**: A JavaScript script is included at the bottom of the code, which handles form submissions. When a user submits the contact form, the data is sent to a Google Apps Script for processing.

### 1.5 HARDWARE AND SOFTWARE REQUIREMENTS

**HARDWARE REQUIREMENTS:**

Computer: A standard personal computer or laptop is sufficient with a resolution of 1024x768 or higher is recommended for a comfortable viewing experience.

**SOFTWARE REQUIREMENTS:**

Text Editor or IDE: You'll need a text editor or IDE to write, edit, and manage your HTML and CSS code. Some of the popular options are Visual Studio Code, Sublime Text, Atom or Notepad++

Web Browser: To view and test HTML, CSS code we need a modern web browser such as Google Chrome, Mozilla Firefox or Opera.

Line-awesome library for icons

Google-fonts

Bootstrap CSS

AOS (Animate on Scroll) Library

Version Control Software like Github to host project

### 2.0 WEB DESIGN TECHNOLOGIES USED

The portfolio project uses a variety of web design technologies such as HTML, CSS, and JavaScript code. Here is a list of the web design technologies and concepts used in the code:

**HTML Structure**  The HTML file defines the structure and content of your web page. It includes headings, paragraphs, links, and various HTML elements that make up the page's content. Semantic elements like `<header>`, `<section>`, `<footer>`, and `<ul>` are used to structure the content and provide meaning to different sections of the web page.

**Bootstrap CSS**

**Navbar Component:** The code includes a navigation bar (navbar) using Bootstrap's .navbar class. It's a responsive navigation bar that collapses on smaller screens and expands on larger screens.

**Button Component:** Bootstrap buttons are used in the "Explore My Work" and "Download CV" links. The classes btn and btn-brand apply Bootstrap button styles.

**Card Component:** Bootstrap cards are used to display information about projects in a visually appealing way. Cards provide a structured layout for presenting content, including images and descriptions.

**Form Component:** The contact form at the bottom of the page uses Bootstrap's form components. It includes form fields for name, email, subject, and a message text area.

**Grid System**: Bootstrap's grid system is used to create responsive layouts throughout the page. Columns and rows are defined using Bootstrap classes such as .row, .col-lg-8, and .col-md-6.

**Responsive Classes**: Bootstrap provides responsive classes like .text-lg-center and .d-none d-lg-block to control the text alignment and display behavior on different screen sizes.

**Button Styles**: The buttons within cards and the contact form are styled using Bootstrap's button classes, such as .btn and .btn-brand.

**Spacing and Margin Classes**: Bootstrap spacing and margin classes like .mt-2, .mb-4, and .py-5 are used to control the spacing and margins between elements.

**Utility Classes**: Bootstrap includes utility classes that help in various styling aspects. For example, classes like rounded-4 are used to add rounded corners to elements.

**CSS**

**Custom Properties (CSS Variables):** Custom properties are defined using :root which allow us to create and manage variables for consistent styling throughout your stylesheet.

**Selectors**: Various CSS selectors are used to target specific HTML elements, including type selectors (e.g., h1, h2, h3), class selectors (e.g., .text-brand), and ID selectors (e.g., #contact).

**Color Properties**: CSS color properties (color, background-color, border-color) are used for text and background colors, including custom colors defined with CSS variables.

**Font Properties**: The font-family property sets the primary font for the webpage, using the "Bai Jamjuree" font and a fallback to a generic sans-serif font.

**Text Styles**: Properties like font-weight, text-transform, and text-decoration are used for text styling.

**Transition and Hover Effects**: The transition property is used to create smooth transitions for various CSS properties. Hover effects are applied to links, buttons, and images.

**Layout and Box Model**: Properties like min-height, display, flex, padding, and border are used to control the layout and spacing of elements.

**Media Queries**: The code includes a media query to apply styles when the viewport width is at least 992px. This is a common technique for responsive web design.

**Keyframe Animations**: Keyframe animations are used to create animated progress bars for skills (HTML, CSS, etc.) and professional skills (communication, creativity, etc.).

**Box Shadow**: The box-shadow property is used to create shadow effects, which are applied on hover (.shadow-effect).

**Gradients:** The linear-gradient property is used for creating a gradient background in the navbar.

**Project Card Hover Effect:** The transform property is used for scaling (zooming) images within project cards when hovered over.

  
**JavaScript**

**Animation:** Initialize the AOS (Animate On Scroll) library, which is a JavaScript library for adding scroll animations to web pages. It's used to create animations when elements come into view as the user scrolls down the page.

**Form Handling:** The script is responsible for handling a form submission on a webpage. When a user submits the form, the script prevents the default form submission action (which would normally refresh the page) using e.preventDefault(). It then sends the form data to a specific web address (URL) represented by scriptURL using a POST request. If the submission is successful, it displays a pop-up message saying, "Thank you! your form is submitted successfully." After the message is displayed, it reloads the page. In essence, this script allows users to submit data through a form on the website, sends that data to a server (specifically, a Google Apps Script web app), and provides feedback to the user once the submission is complete, all without needing to leave or refresh the page.
