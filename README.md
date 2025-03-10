# Weekend Activities Management at King's Academy

Welcome to the Weekend Activities Management project for King's Academy. This initiative aims to streamline and enhance the planning, coordination, and execution of weekend activities for our students, ensuring they have enriching and enjoyable experiences throughout the academic year.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
    - [Activity Scheduling](#activity-scheduling)
    - [Student Participation Tracking](#student-participation-tracking)
    - [Feedback Collection](#feedback-collection)
    - [Communication Platform](#communication-platform)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

King's Academy offers a diverse range of weekend activities designed to foster community, cultural appreciation, and personal growth. These activities include:

- **Cultural Excursions**: Visits to historical sites such as Petra, Jerash, and the Dead Sea.
- **Outdoor Adventures**: Hiking in areas like Wadi Mujib, Wadi Ma'in, and Mt. Nebo.
- **Recreational Activities**: Rock climbing, go-karting, bowling, paintball, and swimming.
- **Entertainment**: Trips to local malls, movie theaters, and adventure parks.
- **On-Campus Events**: Movie screenings, gaming competitions, and sports under the lights.

The Weekend Activities Management system is developed to efficiently manage these activities, ensuring seamless coordination and a positive experience for all participants.

## Features

### Activity Scheduling

- **Calendar Integration**: View and manage upcoming activities in a centralized calendar.
- **Automated Reminders**: Receive notifications about upcoming events and deadlines.

### Student Participation Tracking

- **Registration System**: Students can sign up for activities online.
- **Attendance Monitoring**: Track student attendance and participation rates.

### Feedback Collection

- **Surveys and Polls**: Gather student feedback to assess satisfaction and gather suggestions for future activities.
- **Reporting Tools**: Analyze feedback data to identify areas for improvement.

### Communication Platform

- **Announcements**: Post updates and important information for students and parents.
- **Direct Messaging**: Facilitate communication between activity coordinators, students, and parents.

## Technologies Used

- **Frontend**: React.js for building interactive user interfaces.
- **Backend**: Node.js with Express.js for server-side operations.
- **Database**: MongoDB for storing activity and user data.
- **Authentication**: JSON Web Tokens (JWT) for secure user authentication.
- **Hosting**: Deployed on Heroku for reliable performance.

## Getting Started

To get started with the Weekend Activities Management system, follow the steps below:

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB database setup (local or cloud-based).
- Basic understanding of JavaScript and MERN stack.

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/weekend-activities-management.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd weekend-activities-management
   ```

3. **Install Backend Dependencies**:

   ```bash
   cd backend
   npm install
   ```

4. **Install Frontend Dependencies**:

   ```bash
   cd ../frontend
   npm install
   ```

5. **Set Up Environment Variables**

    - Create a `.env` file in the `backend` directory and add your MongoDB URI and other sensitive information.

6. **Start the Development Servers**

    - **Backend**:

      ```bash
      cd backend
      npm start
      ```

    - **Frontend**:

      ```bash
      cd ../frontend
      npm start
      ```

   The application will be accessible at `http://localhost:3000`.

### Usage

- **Student Access**: Students can register, view, and sign up for activities through the user-friendly interface.
- **Coordinator Access**: Activity coordinators can schedule events, monitor registrations, and communicate with participants.
- **Administrator Access**: Administrators have full access to all features, including data analytics and system settings.

## Contributing

We welcome contributions to enhance the functionality and usability of the Weekend Activities Management system. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add feature'`).
4. Push to your forked repository (`git push origin feature-name`).
5. Submit a pull request detailing your changes.

Please ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

By implementing the Weekend Activities Management system, King's Academy aims to provide students with organized, enjoyable, and memorable weekend experiences, fostering a strong sense of community and personal development. 