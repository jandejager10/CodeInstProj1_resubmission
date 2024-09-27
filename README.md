# CodeInstProj1_resubmission
Resubmission of Milestone Project 1


# Project Name: Gym Website

## Description
This project builds a static front-end website for a gym using HTML5 and CSS3. The website aims to attract new members and inform existing members about classes, facilities, and general information.

## Technologies Used
- HTML5
- CSS3
- Bootstrap (for responsive layout)

## Features
- Responsive design for optimal viewing across devices (mobile, tablet, desktop).
- Clear and user-friendly navigation menus.
- High-quality photos showcasing the gym's environment and equipment. (strugling with free stuff so trying to generate using AI)
- Detailed information on class offerings, including schedules and descriptions.
- Location map, contact details, and opening hours.
- Links to the gym's social media pages or external resources.

## Purpose and Value
The purpose of this website is to provide a simple and user-friendly platform for the gym's potential and existing members. It enables users to:
- Browse class schedules and gym facilities.
- Learn about various fitness classes and facilities.
- Contact the gym or find its location easily.
- View images of the gym's environment through the gallery.

Value to the users:
- It helps potential members make informed decisions by providing all necessary details about the gym.
- Existing members can quickly check class schedules and learn about ongoing events at the gym.

Version Control:
The project code is managed using Git and hosted on GitHub.

## Code Attribution
- Bootstrap CSS framework (used for grid layout): [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- FontAwesome icons (used for icons like phone and email): [FontAwesome Documentation](https://fontawesome.com/)
- Hover.css (used for hover effects): [Hover.css Documentation](http://ianlunn.github.io/Hover/)
- chatgpt.com (used for image creation): [Image creator DALL.E](https://chatgpt.com/)

All other code is custom-written.


## Deployment Procedure
The final version of this project has been deployed using GitHub Pages. To deploy this project on GitHub Pages:
1. Push all code to the `main` branch of the repository.
2. Go to the repository's settings on GitHub.
3. Scroll down to the "GitHub Pages" section.
4. Choose the `main` branch as the source.
5. After saving the settings, the website will be live at `https://your-username.github.io/repository-name/`.


Gym Website Project - Test Plan
**Testing Tools:**

* Manual testing will be conducted using various web browsers on different devices (desktop, mobile) to ensure cross-browser compatibility.

## Testing Documentation
Manual testing was performed across multiple devices (desktop, mobile) and web browsers (Chrome, Firefox, Safari). The following test cases were verified:

**1. Functionality:**

| Test Case ID | Description | Expected Result | Pass/Fail | Comments |
|---|---|---|---|---|
| TC-01 | Access the home page (index.html) | The home page should load successfully and display the gym's name ("Code Gym"). | Pass/Fail | Verify basic functionality and content. |
| TC-02 | Navigate to the "Classes" page (classes.html)  | Clicking the "Classes" navigation link should lead to the classes page. | Pass/Fail | Confirm navigation functionality between pages. |
| TC-03 | Navigate to the "Contact" page (contact.html) | Clicking the "Contact" navigation link should lead to the contact page. | Pass/Fail | Confirm navigation functionality between pages. |
| TC-04 | Navigate to the "Gallery" page (gallery.html) | Clicking the "Gallery" navigation link should lead to the gallery page. | Pass/Fail | Confirm navigation functionality between pages. |
| TC-05 | Submit a contact form | Filling and submitting the contact form should successfully submit the data (without actual functionality of sending emails). | Pass/Fail | Verify form functionality and basic validation (e.g., required fields). |
| TC-06 | Test broken links | Clicking a broken link should display a user-friendly error page (error.html). | Pass/Fail | Ensure proper handling of non-existent links. |

Screenshots from testing:
![Home Page Screenshot](screenshots/homepage.png)

**2. User Experience:**

| Test Case ID | Description | Expected Result | Pass/Fail | Comments |
|---|---|---|---|---|
| TC-07 | Mobile Responsiveness | The website should display correctly and be usable across various screen sizes (desktop, mobile). | Pass/Fail | Verify website layout adapts to different devices. |
| TC-08 | Page Loading Speed | Pages should load reasonably fast for a good user experience. | Pass/Fail | Perform a basic speed test using online tools (subjective assessment). |
| TC-09 | Clear Navigation | The navigation menu should be clear and easy to understand, allowing users to find desired information efficiently. | Pass/Fail | Review navigation structure and labeling for clarity. |
| TC-10 | Image Quality | Images used throughout the website should be high-resolution and visually appealing. | Pass/Fail |  Subjective assessment of image quality and relevance. |

## Code Validation

This website's HTML and CSS code were validated using the following tools to ensure compliance.

### HTML Validation
The HTML code was validated using the [W3C Markup Validation Service](https://validator.w3.org/). All pages passed with no errors.

**Proof of validation**:

![HTML Validation Screenshot](images/html-validation.png)

### CSS Validation
The CSS code was validated using the [W3C CSS Validation Service (Jigsaw)](https://jigsaw.w3.org/css-validator/). The stylesheet passed with no errors or warnings.

**Proof of validation**:

![CSS Validation Screenshot](images/css-validation.png)


**Pass/Fail Criteria:**

* All test cases must pass for a successful website launch.
* Any critical bugs or usability issues discovered during testing will require rectification before deployment.
* Minor visual inconsistencies can be addressed after launch based on priority.

Minor layout inconsistencies or visual adjustments will be documented for future updates.

Testing Tools:
Web Browsers (Chrome, Firefox, Safari, etc.)
Mobile Devices (phones, tablets)
Testing notes and documentation (screenshots, bug reports)

## Folder Structure
main_folder/
├── classes.html
├── contact.html
├── 404.html
├── gallery.html
├── index.html
├── README.md
└── assets/
├── css/
│ └── style.css
  └── images/
└── gym-placeholder.jpg