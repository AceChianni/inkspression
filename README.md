# inkspression
# Inkspression - Interactive Journaling & Neurodivergent-Friendly Productivity Hub

**Inkspression** is a holistic platform designed to provide an interactive journaling experience with a focus on neurodivergent-friendly productivity tools. This web application aims to create a comfortable, organized space for self-expression, mindfulness, and effective task management, all in one place.

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Development](#development)
7. [Contributing](#contributing)
8. [License](#license)

---

## Overview

Inkspression is built to enhance self-care and productivity through an intuitive and accessible design. With features like mood tracking, journaling, affirmation banners, and task management, it serves as a space for introspection, goal-setting, and personal growth.

---

## Features

- **Interactive Journaling**: Write, reflect, and track your thoughts in a seamless interface.
- **Neurodivergent-Friendly Design**: Prioritize accessibility with easy-to-navigate interfaces and features.
- **Mood & Task Tracking**: Log your mood, set daily tasks, and monitor your progress.
- **Affirmation System**: Daily motivational affirmations to uplift your mindset.
- **Customizable Templates**: Use and customize templates for to-do lists, journals, and more.

---

## Tech Stack

- **Frontend**: React, TailwindCSS, Framer Motion (for animations)
- **Backend**: Node.js
- **Database**: Firebase Firestore (real-time data for mood/task logs)
- **PDF Export**: jsPDF or react-pdf
- **Deployment**: Vercel

---


## Installation

1. **Install Dependencies**: Install all the required dependencies using npm:

    ```bash
    npm install
    ```

2. **Tailwind CSS Setup**: Initialize Tailwind CSS in your project (if not already set up):

    ```bash
    npx tailwindcss init
    ```

3. **Start Development Server**: To start the project in development mode:

    ```bash
    npm start
    ```

    This will open the app in your browser at [http://localhost:3000](http://localhost:3000).

---

## Usage

1. **Running the Build**: To compile the Tailwind CSS styles into a single file:

    ```bash
    npm run build:css
    ```

2. **Accessing the Dashboard**: Upon running the project locally, the dashboard will provide access to:
   - **Journal Section**: Write daily entries.
   - **Planner/Task List**: Track and complete your daily tasks.
   - **Affirmations**: View a new affirmation each day.
   - **Insights**: View analytics about your mood and tasks.

---

## Development

This project is still under development, and there are several areas for future improvement:
- Enhance mood-tracking features with additional metrics.
- Integrate more advanced mindfulness features, such as guided meditations or reflection prompts.
- Improve accessibility for neurodivergent users by conducting user testing and making adjustments as needed.

---

## Contributing

We welcome contributions to improve the Inkspression project! To contribute, please follow these steps:

1. Fork this repository.
2. Create a new branch (e.g. `git checkout -b feature-name`).
3. Make your changes and commit them (e.g. `git commit -am 'Add new feature'`).
4. Push to your branch (e.g. `git push origin feature-name`).
5. Submit a pull request with a clear description of your changes.

For any issues or suggestions, please open an issue in the Issues section of the repository.

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

### Customizations you can make:
- **Tech Stack**: Update this section if you want to add or remove specific technologies.
- **Features**: Feel free to change the features listed here if they evolve or if new features are added to the project.
- **Installation/Usage**: Add any additional steps if the process is more specific to your environment or build tools.
- **License**: If you're using a different license, make sure to change the license section accordingly.