# CarDealership — Full-Stack Developer Capstone

## Project Name
**CarDealership — National Car Retailer Web Application**

## Project Description
A full-stack responsive web application built for **Cars Dealership**, a national car retailer in the U.S. The application enables users to browse dealership branches across the country, view customer reviews, and submit their own reviews.

## Technologies Used

### Frontend
- **React.js** — Component-based UI
- **HTML5 / CSS3** — Responsive design
- **Bootstrap 5** — Styling and layout

### Backend
- **Django** — Main web framework
- **Django REST Framework** — REST API
- **SQLite** — Local relational database

### Microservices
- **Flask (Python)** — Product details microservice
- **Node.js / Express** — Dealer pricing microservice
- **MongoDB** — NoSQL database for reviews and dealers

### DevOps & Deployment
- **Docker** — Containerization
- **Kubernetes** — Container orchestration
- **IBM Cloud Code Engine** — Serverless deployment
- **GitHub Actions** — CI/CD pipeline

## Features
- Browse all car dealerships nationwide
- Filter dealerships by U.S. state
- View detailed dealer profiles and customer reviews
- Submit reviews (authenticated users only)
- Sentiment analysis on reviews (positive/neutral/negative)
- User registration, login, and logout
- Django Admin panel for data management
- Fully deployed on IBM Cloud Code Engine

## Repository Structure
```
xrwvm-fullstack_developer_capstone/
├── server/
│   ├── frontend/
│   │   ├── static/
│   │   │   ├── About.html
│   │   │   └── Contact.html
│   │   └── src/
│   │       └── components/
│   │           ├── Register/
│   │           │   └── Register.jsx
│   │           ├── Login/
│   │           └── Dealers/
│   ├── djangoapp/
│   │   ├── models.py
│   │   ├── views.py
│   │   └── urls.py
│   └── djangoproj/
│       └── settings.py
├── .github/
│   └── workflows/
│       └── ci.yml
├── Dockerfile
└── README.md
```

## Author
**Spriha Singh**
GitHub: [@sprihasingh7](https://github.com/sprihasingh7)

## Course
IBM Full-Stack Software Developer Professional Certificate
*Application Development using Microservices and Serverless*