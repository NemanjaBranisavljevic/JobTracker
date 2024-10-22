# Job Application Tracker

## Overview

The Job Tracker is a web application built using the Django framework. This software is designed to help users efficiently manage and track their job applications, providing guidance throughout the application process using AI. The application aims to simplify the job search experience, ensuring that users stay organized and informed.

## Features

- **User-Friendly Interface**: Intuitive design that allows users to easily navigate the application.
- **Application Tracking**: Keep track of multiple job applications, including statuses, dates, and relevant details.
- **AI Guidance**: Receive personalized tips and suggestions based on user input and application progress.
- **Document Management**: Store and manage resumes, cover letters, and other application-related documents.
- **Notifications**: Get reminders for application deadlines, follow-ups, and interviews.
- **Analytics Dashboard**: Visualize application progress and statistics to improve job search strategies.

## Technologies Used

- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (or PostgreSQL, depending on configuration)
- **AI Tools**: Integrated AI models for recommendation and guidance

## Installation

### Prerequisites

- Python 3.x
- Django 3.x (or higher)
- pip

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/job-application-tracker.git
   cd job-application-tracker
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser (optional):
   ```bash
   python manage.py createsuperuser
   ```

6. Run the server:
   ```bash
   python manage.py runserver
   ```

7. Access the application in your web browser at `http://127.0.0.1:8000/`.

## Usage

1. **Register/Login**: Create an account or log in to access your dashboard.
2. **Add Applications**: Enter details about job applications including the company, position, status, and deadlines.
3. **Receive AI Guidance**: Utilize the AI features to get tailored advice based on your application history.
4. **Monitor Progress**: Track the status of each application and receive notifications for important dates.

## Contributing

We welcome contributions! If you’d like to contribute to the Job Application Tracker, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

For support or questions, please open an issue on the GitHub repository or contact us at [nbranisavljevic@yahoo.com].

---

Thank you for using Job Tracker! Happy job hunting!
