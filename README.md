# StudyBud

StudyBud is a student-focused academic platform designed to make university life more organized and collaborative. The platform helps students connect with potential study partners based on their courses and availability while providing a centralized hub for accessing useful campus resources and services.

## Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Tech Stack](#tech-stack)
* [Getting Started](#getting-started)

  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Future Improvements](#future-improvements)

## Overview

StudyBud addresses two key challenges faced by university students: finding suitable study partners and accessing important campus resources.

The platform allows students to discover and connect with other students who share similar courses and study schedules, making it easier to form study groups and prepare for exams together. It also provides a centralized, searchable hub where students can find university services, academic resources, and other useful campus information.

StudyBud was developed as a functional MVP during a 24-hour development sprint, covering the process from ideation and development to deployment.

## Features

* Study partner matching based on courses and availability.
* Centralized hub for campus resources and university services.
* Searchable academic and campus resources.
* User-focused interface for navigating study-related services.
* Backend API for managing application data.
* PostgreSQL database for persistent data storage.
* Deployed MVP for testing and demonstration.

## Tech Stack

* **Frontend:** Next.js
* **Backend:** Django
* **Database:** PostgreSQL
* **Languages:** Python, JavaScript

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

* Node.js and NPM for running the frontend.
* Python for running the Django backend.
* PostgreSQL for the application database.

### Installation

Clone the repository:

```sh
git clone <repository-url>
```

Navigate to the project directory:

```sh
cd StudyBud
```

Install the frontend dependencies:

```sh
npm install
```

Install the backend dependencies:

```sh
pip install -r requirements.txt
```

Run the database migrations:

```sh
python manage.py migrate
```

Start the Django development server:

```sh
python manage.py runserver
```

Start the frontend application:

```sh
npm run dev
```


