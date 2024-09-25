
# EduVista21

EduVista21 is an innovative e-learning platform designed to bridge the digital divide and provide equitable access to quality education for students regardless of their geographical location or socioeconomic status.
## Contributor
-[Vootukuru Jyotheesh] @Jyotheeshgoud

## Table of Contents

- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)


## About

EduVista21 offers a comprehensive suite of educational tools and resources, providing students with access to a diverse range of courses, career guidance, and job opportunities. Our platform ensures that students from various backgrounds can access quality education and stay informed about the latest market trends and career paths.

## Features

- Extensive library of courses
- Career guidance from industry professionals
- Direct access to job listings
- Real-time communication and notifications
- Mentorship programs and peer-to-peer learning

## Technologies Used

### Frontend
- **Vue.js**: For building a dynamic and responsive user interface
- **Vue Router**: For client-side routing and navigation
- **Axios**: For making HTTP requests to our backend APIs
- **Tailwind CSS**: For a modern and flexible styling approach

### Backend
- **PHP**: As the core scripting language for server-side logic
- **Laravel**: A powerful PHP framework for server-side logic and API development
- **MySQL**: For database management and data storage
- **Redis**: For caching and enhancing performance
- **Laravel Passport**: For secure API authentication
- **Docker**: For containerization, ensuring consistency across different environments

### Middleware
- **Laravel Middleware**: To handle HTTP requests and responses efficiently
- **Laravel Echo and Pusher**: For real-time communication and notifications

### Development Tools
- **Laravel Mix**: Asset compilation, minification, and versioning
- **Composer**: Dependency management for PHP
- **npm**: Package management for JavaScript

## Installation

### Prerequisites

- PHP (>=7.4)
- Composer
- Node.js and npm
- Docker (optional, for containerization)

### Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/HEMASRI2175/Eduvista21.git
   cd eduvista
   ```

2. **Install PHP dependencies:**
   ```sh
   composer install
   ```

3. **Install JavaScript dependencies:**
   ```sh
   npm install
   ```

4. **Set up environment variables:**
   Copy `.env.example` to `.env` and update the necessary settings.

5. **Generate application key:**
   ```sh
   php artisan key:generate
   ```

6. **Run database migrations:**
   ```sh
   php artisan migrate
   ```

7. **Install Passport:**
   ```sh
   php artisan passport:install
   ```

8. **Compile assets:**
   ```sh
   npm run dev
   ```

9. **Start the local development server:**
   ```sh
   php artisan serve
   ```

## Usage

To use EduVista21, follow the installation steps above to set up the development environment. Once set up, you can access the platform via the local development server and start exploring the features.

## API Documentation

### Authentication

EduVista uses Laravel Passport for secure API authentication.

### Endpoints

- **User Registration**: `POST /api/register`
- **User Login**: `POST /api/login`
- **Fetch All Courses**: `GET /api/courses`
- **Enroll in a Course**: `POST /api/courses/{id}/enroll`
- **Fetch Enrolled Courses**: `GET /api/user/courses`
- **Post a Job**: `POST /api/jobs`
- **Fetch All Jobs**: `GET /api/jobs`
- **Fetch a Specific Job**: `GET /api/jobs/{id}`

