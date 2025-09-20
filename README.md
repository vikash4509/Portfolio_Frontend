<img width="1906" height="908" alt="image" src="https://github.com/user-attachments/assets/cd631abe-414d-47f8-b1f6-506be75be515" /># portfolio frontend

## Project Objective
The objective of the Portfolio Frontend is to design and develop an interactive, user-friendly, and responsive web interface that showcases personal information, skills, achievements, and projects.

This frontend project ensures:

  . A visually appealing and modern UI/UX.
  
  . Seamless navigation between different sections.
  
  . Integration with the backend API for handling user interactions like submitting the contact form.
  
  . Responsiveness across devices.

  The aim of this project is to create a complete MERN-based Portfolio Website that highlights personal skills, achievements, and projects while providing a professional platform for visitors to connect.

---

## Brief Description
The Portfolio Frontend is a React-based web application that provides an elegant and responsive interface for showcasing personal information, skills, projects, and achievements.It also includes a contact form where users can send messages, which are forwarded to the backend for storage in MongoDB.
---

## Links
**GitHub Repository:** - https://github.com/vikash4509/Portfolio_Frontend.git

**Live Demo:**
---

**##Technologies Used**

HTML5 & CSS3

JavaScript (ES6+)

React.js (Vite)

React Bootstrap

**##How to Run Locally**

Clone the repository

Bash

git clone https://github.com/vikash4509/Portfolio_Frontend.git
Navigate into the project folder

Bash

cd portfolio-frontend
Install dependencies

Bash

npm install
Start the development server

Bash

npm run dev


**##Challenges Faced & Solutions**
*Challenge:* Cross-Origin Resource Sharing (CORS) Errors

*Solution:* Configured the backend Node.js server with a flexible CORS policy to accept requests from both the main Vercel production domain and dynamic preview URLs generated during development.

*Challenge:* Deployment Bugs on Render

*Solution:* Debugged several Module Not Found errors caused by case-sensitivity differences between the local Windows environment and the Linux-based deployment server. Corrected all file import paths to ensure they matched the exact casing of the filenames.

*Challenge:* Corrupted Local Git Repository

*Solution:* Resolved a fatal: in unpopulated submodule error by identifying and removing a nested, accidental Git repository within the project structure, which allowed for a clean commit and push history.


## Screenshots

![Image](https://github.com/user-attachments/assets/80a80c5e-750c-4bd3-bdbb-1cabb7e9187c)
The screenshot shows the homepage of a personal portfolio website for a "MERN Stack Developer" and self-introduction.
<img width="1909" height="1079" alt="Image" src="https://github.com/user-attachments/assets/503e746b-1f7a-46f5-a371-726781906116" />
The screenshot shows the "About Me" page of a personal portfolio website.
<img width="1419" height="1056" alt="Image" src="https://github.com/user-attachments/assets/9d343a66-2b72-4af4-afed-779e6acc4090" />
This screenshot demonstrates the Frontend Projects Page of your portfolio website, where different projects are showcased with their status.
<img width="1910" height="903" alt="Image" src="https://github.com/user-attachments/assets/d9ccd4e2-4d9a-4228-930d-7d8be0c75d39" />
The screenshot shows the "Resume & Experience" page of a personal portfolio website being viewed in a web browser.
<img width="1906" height="908" alt="Image" src="https://github.com/user-attachments/assets/d8455aaf-826d-46e5-8e3c-55455e178854" />
The screenshot shows a "Contact" page with a form to send a message.
---

## Feature List
- Homepage
- About Section
- Projects Section, Resume Section, Contact Section
- Dark/Light Mode Toggle
- Responsive Design
- Fast Performance

---

## Sample Input & Output
✅ Sample Input 

A visitor fills out the contact form on your portfolio website:

 1. Name: Vikash Gupta

 2. Email: vikas1182004@gmail.com

 3. Message: "Hi, I really liked your projects. Can we connect for a collaboration?"

✅ Sample Output

. User clicks "Submit" button.

. A success notification (e.g., "Your message has been sent successfully!") appears on the frontend.

. The form fields are cleared for new input.

📷 Screenshot Evidence (Frontend Output)

 . Contact form page after submission.

 . Form resets showing empty fields.

---

## Evaluation Criteria Mapping

| Criteria                |                  	              Implementation in Project                                                    |
|---------------------    | --------------------------------------------------------------------------------------------------------------|
| Project Objective       |  Built a personal portfolio website to showcase projects, skills, and provide a way for visitors to connect.  |
| Frontend Development    |  Created using React (Vite), with reusable components for Home, About, Projects, Resume, and Contact sections.|
|Design & Responsiveness  |  Fully responsive layout with modern UI/UX design, smooth navigation, and theme customization.                |
|Features Implemented     |  Project showcase cards, resume download link, contact form with validation, smooth scroll navigation,        |
|                         |     dark/light theme toggle.                                                                                  |
|Interactivity            |  Contact form input and submission, responsive navigation bar, interactive project status labels.             |
|Challenges & Solutions   |  Faced issues with routing, CSS styling conflicts, and form validation — solved using React Router,           |
|                         |       modular CSS, and custom hooks.                                                                          |
|Documentation            |  README includes objective, description, technologies used, setup instructions, screenshots,                  |
|                         |          sample input/output, and proof of working.                                                           |
| Sample Input/Output     |  Demonstrated contact form submission, success alert on frontend, and MongoDB entry on backend.               |

---
## Author

*Name:*  Vikash Kumar Gupta

*Date:* 20 september 2025
