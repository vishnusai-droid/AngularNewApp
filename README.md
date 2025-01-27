# First App Angular Project

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [License](#license)

## Project Description
The **First App Angular Project** is a beginner-friendly web application built with Angular. This project serves as a template for learning Angular's core features, including components, services, routing, and data binding.

This app also demonstrates the integration of a mock database (`db.json`) to simulate backend operations, making it ideal for understanding the basics of full-stack development.

## Features
- Responsive UI using Angular components.
- Mock API integration with `db.json` for data storage.
- Clean and modular project structure.
- Demonstrates Angular services for managing data.
- Basic routing setup with Angular's RouterModule.

## Tech Stack
- **Frontend:** Angular, TypeScript, HTML, CSS
- **Backend:** JSON Server (for mock API)
- **Build Tool:** Angular CLI

## Setup and Installation
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd first-app-angular-main
   ```

2. **Install dependencies:**
   Make sure you have [Node.js](https://nodejs.org/) installed. Then, run:
   ```bash
   npm install
   ```

3. **Run JSON Server:**
   Start the mock backend server using JSON Server:
   ```bash
   npx json-server --watch db.json
   ```

4. **Run the Angular application:**
   ```bash
   ng serve
   ```
   The app will be available at `http://localhost:4200/`.

## Usage
- Open your browser and navigate to `http://localhost:4200/`.
- Explore the app's features.
- Use the mock database (`db.json`) for CRUD operations.

## Project Structure
```plaintext
first-app-angular-main/
├── e2e/                # End-to-end test files
├── src/
│   ├── app/
│   │   ├── app.component.ts    # Main component logic
│   │   ├── app.component.html  # Main component template
│   │   ├── app.component.css   # Main component styles
│   │   ├── housing.service.ts  # Service for managing data
│   ├── assets/         # Static assets
│   ├── environments/   # Environment configurations
│   ├── favicon.ico     # Application favicon
│   ├── index.html      # Root HTML file
│   ├── main.ts         # Application bootstrap
│   ├── styles.css      # Global styles
├── angular.json        # Angular CLI configuration
├── package.json        # NPM dependencies and scripts
├── tsconfig.json       # TypeScript configuration
├── db.json             # Mock database
```

## Contributors
- **Your Name**  
  Role: Developer  
  Contact: [Your Email](mailto:fowzaan.rasheed@gmail.com)

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
