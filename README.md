
# StoryCrafter

## Overview
StoryCrafter is a web application that generates unique stories from user-uploaded images. It uses AWS Rekognition to analyze images and extract key elements, which are then processed by OpenAI’s API to create an engaging narrative. Users can save and manage their generated stories in a personal archive.

## Features
- **AI-Generated Stories** – Upload an image, and AI will generate a unique story based on detected elements.
- **Story Summarization** – Get a quick summary of each generated story for easy reference.
- **User Accounts** – Secure login and authentication to manage user-generated content.
- **Personal Archive** – View, store, and revisit past generated stories.
- **Cloud Storage & Hosting** – Securely store stories in AWS DynamoDB and host the application on AWS EC2.
- **Serverless Backend** – Use AWS Lambda for efficient and scalable backend operations.

## Project Structure
The project is structured into frontend, backend, and logic components:
```
StoryCrafter/
│── index.html              # Homepage
│── index.php               # Server-side logic for homepage
│── info.php                # Information page
│── login.html              # Login page
│── login.php               # Login authentication
│── login.js                # Client-side login logic
│── loginstyle.css          # Login page styles
│── logout.php              # Logout function
│── my-account.php          # User account management
│── script.js               # General JavaScript functions
│── search-function.py      # Image and story search logic
│── sign-up.php             # User registration
│── signup.html             # Signup page
│── signup.js               # Signup form validation
│── signupstyle.css         # Signup page styles
│── style.css               # Global stylesheet
│── UploadImage.php         # Handles image uploads
│── view-story.php          # Displays generated stories
│── README.md               # Project documentation
```

## Technologies Used
StoryCrafter is built using:
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP, AWS Lambda
- **AI & Processing:** AWS Rekognition, OpenAI API
- **Database & Storage:** AWS DynamoDB
- **Hosting:** AWS EC2
