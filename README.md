# Best Cars Dealership — Full-Stack Application Development Capstone

## Project Overview
**Best Cars Dealership** is a responsive full-stack web application built for a national car retailer in the United States. The platform allows visitors and registered customers to browse dealership branches nationwide, filter locations by U.S. state, inspect customer reviews, and submit new dealership reviews with automated sentiment analysis.

## Architecture & Tech Stack
* **Frontend:** React, Bootstrap, HTML5, CSS3
* **Backend Gateway & Auth:** Python Django, SQLite
* **Dealership & Reviews Microservice:** Node.js, Express, MongoDB
* **Sentiment Analysis Microservice:** Python Flask / NLTK (deployed via IBM Cloud Code Engine)
* **DevOps & Deployment:** GitHub Actions (CI/CD), Docker, Kubernetes

## Key Features
* **User Authentication:** Full sign-up, login, and logout flows managed via Django authentication and React components.
* **Dealership Directory:** Dynamic listing of all U.S. dealership branches with state-based filtering.
* **Dealer Reviews & Sentiment Analysis:** Customers can read reviews per dealership and post new reviews evaluated in real time as positive, neutral, or negative.
* **Admin Management:** Django Admin interface for managing car makes, car models, and user accounts.