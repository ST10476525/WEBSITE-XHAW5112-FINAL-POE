# WEBSITE-XHAW5112-FINAL-POE
Precious Radebe Website
README — Empowering the Nation Website & Mobile App
 Project Overview
 Empowering the Nation is a skills-development initiative founded by Precious Radebe in 2022. The
 SME offers six-month Learnerships and six-week Short Skills Training Programmes aimed at
 empowering domestic workers and gardeners with professional, marketable skills.
 This project delivers a fully functional responsive website where customers can:
 • View summaries of all courses
 • View detailed course pages
 • Calculate course fees with automatic discounts
 • Request a quote via a contact form
 • Navigate easily using a clean UI, dropdown menus, and back-button system
 Features Implemented
 1. Home Page- Displays company mission and overview- Shows a preview of courses- Includes navigation to course summaries, quote page, and contact form
 2. Course Management
 All course data is stored in a JavaScript COURSES array.
 Includes ID, title, fee, duration, type, purpose, content, and images.
 3. Course Summary Pages
 Two pages display:
 • Six-month courses
 • Six-week courses
 Each dynamically generates course cards with title, duration, fee, and a Details button.
 4. Detailed Course Pages
Each course detail page displays:
 • Title
 • Duration
 • Purpose
 • Full content list
 • Fees
 • Add to Form button (auto-selects course in quote calculator)
 5. Quote Calculator Page
 Includes:
 • Contact form (Name, Phone, Email)
 • Checkboxes for courses
 • Discount calculation:- 1 course: 0%- 2 courses: 5%- 3 courses: 10%- >3 courses: 15%
 • VAT calculation (15%)
 • Full invoice generation with totals
 6. Navigation System
 Uses hash-based routing (#home, #six-month, #short-courses, etc.).
 Includes:
 • Back button functionality
 • Quick navigation dropdown
 • Browser history using pushState
 7. Visual & UX Features
• Fade-in transition on page loads
 • Responsive cards
 • Structured layout and green professional theme
 Technical Structure
 Technologies Used:
 • HTML5
 • CSS3
 • JavaScript (Vanilla)
 Main Components:
 • COURSES array — all course data
 • Routing system — hash-based SPA navigation
 • Form validation
 • Invoice generation
 • Dynamic course card creation
 Discount & VAT Calculation
 VAT = 15%
 Discount rules based on number of courses selected.
 Error Handling
 Includes various validations such as:
 • Incorrect phone numbers
 • Invalid emails
 • Missing required fields
 • Missing course selections
 Running the Website
1. Place all files including Images folder in one directory.
 2. Open index.html in any browser.
 3. No server required.
 Future Enhancements
 • Add backend storage for quotes
 • Convert to PWA
 • Add notifications
 • Add admin portal
Screenshots
<img width="1365" height="710" alt="Screenshot 2025-10-30 195725" src="https://github.com/user-attachments/assets/2e3f8ad1-c68d-4bb9-81bf-c3016d2a2588" />
[Mobile app and website prototype.docx](https://github.com/user-attachments/files/23609055/Mobile.app.and.website.prototype.docx)
<img width="1365" height="712" alt="Screenshot 2025-10-30 201836" src="https://github.com/user-attachments/assets/be6637da-b7f2-41b6-8745-79f625823457" />
------------------------------------------------------
Youtube link
https://youtu.be/CgSqFkS-Efw?si=yJGL9iV6kykCK_Zz
