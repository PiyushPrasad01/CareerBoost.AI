# CareerBoost.AI

Welcome to CareerBoost.AI, your comprehensive platform designed to prepare engineering graduates for their dream jobs. This repository contains the codebase for the CareerBoost.AI platform, providing personalized roadmaps, mentorship, skill assessments, and more to ensure you are fully prepared for your job placement.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

CareerBoost.AI is an end-to-end solution aimed at helping engineering students and graduates secure their dream jobs. Our platform offers a variety of tools and resources, including personalized roadmaps, skill assessments, mentorship from senior developers, and an AI interview assistant. Users can access curated courses, improve their skills, and explore job opportunities, all tailored to their specific career goals.

## Features

- **Personalized Roadmaps and Weekly Timelines**: Customizable plans based on user needs and goals.
- **Profile Setup**: Easily set up your profile with resume upload and GitHub integration for project retrieval.
- **Skill Assessment and Gap Analysis**: LeetCode-style skill assessments to identify and address knowledge gaps.
- **Mentorship**: Access to senior developers through a pay-to-talk model, with payment only upon successful placement.
- **AI Interview Assistant**: Practice and improve your interview skills with the help of our AI assistant.
- **Attention Span and Skill Monitoring**: Track your progress and stay focused with our monitoring tools.
- **Curated Courses and Job Portal**: Explore and enroll in courses to enhance your skills and access job listings.

## Technologies Used

- **Django**: The web framework used for building the platform.
- **GitHub API**: For integrating users' GitHub profiles and retrieving project information.
- **Gemini**: Used for skill assessment and gap analysis.
- **Voice Recognition**: Enables the AI interview assistant to interact with users.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/CareerBoost.AI.git
    ```
2. Navigate to the project directory:
    ```sh
    cd CareerBoost.AI
    ```
3. Create a virtual environment:
    ```sh
    python -m venv env
    ```
4. Activate the virtual environment:
    - On Windows:
        ```sh
        .\env\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source env/bin/activate
        ```
5. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
6. Apply the migrations:
    ```sh
    python manage.py migrate
    ```
7. Start the development server:
    ```sh
    python manage.py runserver
    ```

## Usage

Once the development server is running, you can access the platform by navigating to `http://127.0.0.1:8000/` in your web browser. From there, you can create an account, set up your profile, and start exploring the various features of CareerBoost.AI.

## Contributing

We welcome contributions to CareerBoost.AI! If you have suggestions for new features or improvements, please open an issue or submit a pull request. Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature/YourFeatureName
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/YourFeatureName
    ```
5. Open a pull request.

Please make sure to update tests as appropriate and adhere to the project's coding conventions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or inquiries, please contact us at support@careerboost.ai.

---

Thank you for using CareerBoost.AI! We hope our platform helps you achieve your career goals and secure your dream job.

