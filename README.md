Clove Dental Landing Page

This project is a responsive, single-page promotional landing page for a dental service, designed to capture user leads and highlight key services and statistics. It is built entirely using standard web technologies (HTML, CSS, and Vanilla JavaScript) 
🌟 Key Features

The application is structured to provide information and drive user conversion, incorporating the following sections:

Header & Navigation (.header): Contains the brand name, a quick-access phone number, and a primary "Book Appointment" button.

Hero Section with Lead Form (.cards-container):

A prominent promotional card highlighting a specific service (e.g., Painless Root Canal Treatment).

A dedicated contact form (.right-card) for immediate consultation booking.

Includes a functional Captcha verification mechanism for spam prevention (implemented in index.js).

Statistics Marquee (.bottom-strip): An animated, horizontally scrolling section showcasing the brand's key performance indicators (e.g., Clinic count, Dentist count, Happy Patients).

Treatment Details (.info-card-section): Detailed breakdown of service types and starting prices.

Client Results Gallery (.smiles-card-section): Displays before-and-after style results or patient success stories.

Testimonials Slider (.patient-stories-section): A horizontal, scrollable section for patient feedback, supporting mouse wheel scrolling via JavaScript.

FAQ/QA Section (.faq-card-section): Implements an interactive Accordion system (controlled by JavaScript) to expand and collapse answers.

Footer (.footer-section): Contains legal links, copyright information, and developer attribution.

🛠️ Technology Stack

HTML: Semantic structure for the entire page.

CSS: Styling and responsive design via media queries (stored in style.css).

JavaScript (Vanilla JS): Handles client-side interactivity, including the Captcha logic, FAQ accordion, and horizontal scroll event listeners.

🚀 Setup and Installation

To run this project locally, follow these simple steps:

Clone the Repository (or download the files):

git clone [repository-url]
cd clove-dental-landing


Ensure File Structure:
Verify that the following files are present in your root directory:

.
├── index.html
├── style.css
├── index.js
└── assets/ (Directory containing all necessary images: Doctor.png, faq.png, smile-1.png, etc.)


Run the Application:
Open the index.html file directly in your web browser.

# Example command (may vary by OS)
open index.html 


📱 Responsiveness

The design is fully responsive and optimized for mobile devices (down to 320px width) through comprehensive CSS media queries (@media (max-width: 768px)). Key layout adjustments include:

Converting the Header and Hero section from a horizontal layout to a vertical stack.

Making the Treatment Cards and Gallery sections horizontally scrollable (overflow-x: auto) for better mobile browsing experience.

Hiding non-essential elements like the desktop "Book Appointment" button on mobile.
