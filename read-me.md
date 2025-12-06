# CSE211 Web Programming – Assignment 1
## EduConnect Online Learning Platform
### Fall 2025-2026

**Group 5:**
- Samaa Mohamed Saleh Hussein Abdelhamid (ID: 223101629) - CE (Cybersecurity)
- Omar Mohamed Gamaleldin Masoud Khalifa (ID: 223101614) - CE (Cybersecurity)

**Instructor:** Prof. Samy Ghoniemy

---

## Project Overview
This is a semantic HTML5 website for an online learning platform called EduConnect, developed as part of the CSE211 Web Programming course at Galala University. The project includes multiple pages, a registration form, a calculator, and performance analysis documentation.

---

## Folder Structure
Group05_223101629_223101614_CSE211_ASS1/
├── Part1_Performance_Analysis/
│ ├── Performance_Analysis_Report.pdf
│ └── screenshots/
│ ├── website1_pagespeed_mobile.png
│ ├── website1_pagespeed_desktop.png
│ ├── website2_pagespeed_mobile.png
│ ├── website2_pagespeed_desktop.png
│ ├── website3_pagespeed_mobile.png
│ └── website3_pagespeed_desktop.png
├── Part2_Project/
│ ├── index.html
│ ├── pages/
│ │ ├── about.html
│ │ ├── contact.html
│ │ ├── course-catalog.html
│ │ ├── course-detail.html
│ │ ├── privacy.html
│ │ ├── registration.html
│ │ ├── student-dashboard.html
│ │ ├── terms.html
│ │ └── thank.html
│ ├── css/
│ │ └── (empty - for future use)
│ ├── scripts/
│ │ └── (empty - for future use)
│ ├── videos/
│ │ └── (empty - for future use)
│ └── images/
│ ├── logo.png
│ ├── map.gif
│ ├── badges/
│ │ └── (badge images)
│ ├── courses/
│ │ ├── (course thumbnail images)
│ │ └── (course hero images)
│ └── profile/
│ └── (profile pictures for users/instructors)
├── Part3_Documentation/
│ ├── Browser_Testing_Report.pdf
│ ├── AI_Documentations.pdf
│ └── Validation_Report.pdf
└── Part4_Calculator/
├── calculator.html
└── calculator-result.html

--AI Gneretaed so the strcucture of lines can be correct. 

---

## Pages Included
1. **Homepage** (`index.html`) - Main landing page
2. **About Us** (`pages/about.html`) - Course information and objectives
3. **Contact Me** (`pages/contact.html`) - Contact information and map
4. **Registration** (`pages/registration.html`) - Complete student registration form
5. **Thank You** (`pages/thank.html`) - Registration confirmation page
6. **Course Catalog** (`pages/course-catalog.html`) - Browse and filter courses
7. **Course Detail** (`pages/course-detail.html`) - Detailed course information
8. **Student Dashboard** (`pages/student-dashboard.html`) - Student progress and activity
9. **Calculator** (`Part4_Calculator/calculator.html`) - Scientific calculator interface
10. **Calculator Result** (`Part4_Calculator/calculator-result.html`) - Calculation results
11. **Privacy Policy** (`pages/privacy.html`) - Privacy policy placeholder
12. **Terms of Service** (`pages/terms.html`) - Terms of service placeholder

---

## Validation & Testing
- All pages validated with W3C Markup Validator
- Tested in Google Chrome and Safari
- Cross browser compatibility confirmed
- All form validations working correctly
- Navigation links properly functional

---

## AI Tools Usage
Note: Different and a lot of AIs were used to generate well structure where spacing, lines, folders structure and code structure could all ensure readability. So a lot of code sections were pasted multiple times and edited. All code was manually written by us but structured used AI at the end.

### 1. Which AI Tools We Used
Primary AI Tools:
- ChatGPT: Main explanation tool for HTML concepts, tags, and attributes
- Grok: Assignment interpretation and structural guidance
- DeepSeek: Code validation against specifications and error resolution
- Gemini: Tag reference, attribute clarification and image generation

Secondary Resources:
- W3Schools reference cross-checking
- MDN Web Docs verification

### 2. How We Used These Tools

**Assignment Understanding & Structure (Grok, DeepSeek)**
- Used Grok to interpret ambiguous assignment requirements and understand intended learning outcomes
- Used DeepSeek to map assignment specifications to practical implementation
- Consulted both tools when assignment instructions were vague or required clarification
- Used Grok to understand which HTML5 elements were considered semantic
- Used DeepSeek to ensure our implementation matched all detailed requirements from the PDF

**Report Documentation Assistance (DeepSeek)**  
Used DeepSeek to:  
- Generate brief introductions and conclusions for validation and browser testing reports, ensuring conventional structure while manually editing for our context  
- Understand best methods for report formatting and content organization  

**HTML Syntax & Structure (ChatGPT, Google AI)**
- Asked ChatGPT to explain the <marquee> element, its attributes (behavior, direction, scrollamount), and why it's deprecated
- Used ChatGPT to understand Google Maps embedding via <iframe> with attributes: width, height, loading="lazy", allowfullscreen, referrerpolicy
- Consulted Google AI for tag syntax verification (whether tags are self-closing, required attributes, proper nesting)
- Asked ChatGPT to explain proper two-column layout implementation using <table> with width attributes (70%/30%) without CSS
- Used ChatGPT to understand <details> and <summary> elements for expandable content sections

**Form Development & Validation (Claude, DeepSeek)**
- Used Claude extensively to understand:
  - Form element hierarchy: <form> → <fieldset> → <legend> → form controls
  - Form validation attributes: required, pattern, minlength, maxlength, min, max
  - Input types: checkbox, radio, range, date, file, email, number
  - Button types: submit, reset, button and their behaviors
  - <textarea> attributes: rows, cols, maxlength, placeholder
  - <select> with <optgroup> for categorized dropdowns
- Used DeepSeek to validate that our forms complied with all assignment specifications:
  - Required field structure for registration form
  - Proper accessibility attributes (for, id, aria-label)
  - Form method (GET) and action (thank.html) compliance whether to use or not since assignment said "If using GET"
  - Hidden field implementation (formVersion, submissionDate, userAgent)

**Semantic HTML & Code Quality (DeepSeek)**
- Verify semantic element usage met assignment requirements
- Check heading hierarchy compliance (h1→h2→h3 progression)
- Validate proper nesting and indentation standards
- Confirm accessibility features were implemented

**Code Validation & Problem Solving (DeepSeek, ChatGPT)**
Used DeepSeek to:
- Validate HTML5 compliance with assignment specifications
- Check for missing required elements or attributes
- Learn approaches solve to W3C validator errors without CSS
- Verify cross browser compatibility considerations

Asked ChatGPT about:
- Differences between GET and POST form methods for our implementation
- W3C validator error resolution strategies without CSS
- Alternative solutions to deprecated attributes while maintaining HTML-only constraints

**Code Organization & Cleanup (Grok)**
Used Grok to:
- Understand optimal code structure and organization patterns
- Remove unnecessary whitespace and empty lines
- Establish consistent indentation standards (2-space vs 4-space)
- Create logical code sections with clear commenting

**Lecture Gap Compensation (All AI Tools)**
Since we haven't attended forms lecture yet, we used AI to:
- Understand fundamental HTML5 concepts that would have been covered in class using old sources at first
- Understand form handling concepts without JavaScript backend
- Comprehend assignment's goals despite missing direct instruction

### 3. What We Learned from Using These Tools
- Accessibility Principles: Importance of alt text, ARIA labels, proper heading hierarchy, keyboard navigation support
- Code Quality: Consistent indentation, meaningful comments, proper attribute ordering, clean file organization
- Validation Standards: Understanding W3C validation purposes and limitations within educational constraints
- Learning Progression: Using AI to fill knowledge gaps allowed us to complete the assignment while genuinely learning the material
- Specification Compliance: How to interpret and implement detailed assignment requirements

### 4. How We Ensured Understanding
- Testing Process: Manual Code Writing: All code was typed manually, with AI only providing explanations or ideas / snippets
- Line-by-Line Review: Each line of code was reviewed and understood before inclusion

### 5. Confirmation of Understanding
I, Samaa Mohamed Saleh and I, Omar Mohamed GamalEldin confirm that all code was manually written with AI tools used only for guidance and explanation or ideas. We understand every line of submitted HTML code and can explain its purpose.

We documented all AI usage transparently as required. The AI tools served as educational support, explaining concepts, suggesting structures, and helping interpret requirements. But all implementation decisions, testing, and final code quality are our own work and understanding.

---

## Submitted Documentation (PDFs)
1. **Performance_Analysis_Report.pdf** - Core Web Vitals analysis of three websites
2. **Browser_Testing_Report.pdf** - Cross-browser compatibility testing results
3. **Validation_Report.pdf** - W3C HTML validation results for all pages
4. **AI_Documentations.pdf** - Detailed documentation of AI tool usage

---

## Submission Details
**Submitted on:** December 6, 2025  
**Platforms:** CANVAS (zipped) & GitHub (Public repository)  
**Filename:** Group05_223101629_223101614_CSE211_Ass1.zip  
**Root Folder:** Group05_223101629_223101614_CSE211_ASS1

---

## Institution
Galala University  
Faculty of Computer Science and Engineering  
Powered by Arizona State University®