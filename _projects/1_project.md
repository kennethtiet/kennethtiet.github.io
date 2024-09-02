---
layout: page
title: NoteIt
description: A full-stack note-taking application
img: assets/img/noteit/stickynotes.jpg
importance: 1
category: work
related_publications: false
toc:
  sidebar: left
---

# What is NoteIt?

NoteIt is a user-friendly note-taking application designed to help you stay organized and productive. Built with Django, it features an intuitive interface for managing your notes efficiently.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/noteit/noteit1.jpg" title="NoteIt Example Picture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Quickly add and remove notes with just a few clicks.
</div>

### Key Features

- **Register and Login:** Securely create and access your account from anywhere.
- **Create and Delete Notes:** Easily manage your notes with a clean and simple interface.
- **Seamless Navigation:** Find and organize your notes effortlessly.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/noteit/noteit2.jpg" title="Register image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/noteit/noteit3.jpg" title="Login image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Secure login and registration for easy access to your notes.
</div>

### Tech Stack

- **Frontend:** React
- **Backend:** Django, Python
- **Database:** PostgreSQL

# Design Process

### User-Centered Approach

Focused on simplicity and ease of use with an intuitive interface and clean layout to minimize distractions.

### Responsive Design

Fully responsive design ensures seamless access across desktops, tablets, and smartphones.

# Architecture

### Frontend

Built with React for reusable components and real-time UI updates.

### Backend

Uses Django and DRF for user authentication, note storage, and CRUD operations.

### Database

PostgreSQL for robust, scalable data management and organization.

### Authentication

Secured with JSON Web Tokens (JWT) via the `djangorestframework-simplejwt` package for token-based API access.

### File Structure

```
noteit_project/
├── backend/
│   ├── api/
│   │   ├── migrations/
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── serializers.py
│   │   ├── tests.py
│   │   ├── urls.py
│   │   └── views.py
│   ├── backend/
│   │   ├── __init__.py
│   │   ├── asgi.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── manage.py
│   ├── requirements.txt
│   └── .env
├── frontend/
│   ├── public/
│   │   ├── vite.svg
│   ├── src/
│   │   ├── components/
│   │   │   ├── Form.jsx
│   │   │   ├── LoadingIndicator.jsx
│   │   │   ├── ProtectedRoute.jsx
│   │   │   └── Note.jsx
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── NotFound.jsx
│   │   │   └── Register.jsx
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   ├── api.js
│   │   └── styles/
│   │   │   ├── Home.css
│   │   │   ├── LoadingIndicator.css
│   │   │   ├── Note.css
│   │   │   └── Form.css
|   ├── index.html
|   ├── vite.config.js
│   ├── .gitignore
│   ├── package.json
│   ├── package-lock.json
│   ├── .env
│   └── README.md
└── README.md
```

# Takeaways

### What I learned

I’ve learned that Django streamlines web development with its core components. These elements together make Django a powerful tool for building web applications efficiently.

- Models define database structure, views handle request and response logic, and serializers convert data to and from JSON for APIs.
- URLs route requests, while forms manage user input and validation.
- The admin interface simplifies data management, authentication controls user access, and middleware processes requests and responses globally.
- Settings configure project behavior.

### Improvements

- User interface: While simple, it could be more creative to make it more visually stimulating and fun to use
- Enhance User Experience: Continuously gather user feedback and refine the UI/UX to make the application more intuitive and user-friendly.
- Expand Authorization: Integrate other third-party authentication services to provide users with more flexible sign-in options
- Add Testing: Increase the coverage of unit and integration tests to ensure the robustness of your application and catch potential issues early.
- Improve or expand documentation for better clarity and ease of use, including setup guides, API documentation, and user manuals.
