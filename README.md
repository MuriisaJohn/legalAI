# Legal Assistant Project

This is a chatbot that helps with Ugandan laws 

## Overview
The Legal Assistant project is a web application designed to analyze legal documents and provide structured insights. It utilizes TypeScript for the backend logic and includes a frontend interface for user interaction.

## Project Structure
```
legal-assistant
├── docs
│   ├── index.html        # Main HTML file for the web application
│   ├── css
│   │   └── styles.css    # Styles for the web application
│   ├── js
│   │   └── main.js       # JavaScript code for interactive functionality
│   └── assets            # Directory for additional assets (images, fonts, etc.)
├── src
│   ├── features
│   │   └── documents
│   │       └── document-service.ts  # TypeScript code for document analysis service
├── .github
│   └── workflows
│       └── deploy.yml    # GitHub Actions workflow for deployment
├── package.json           # npm configuration file
├── tsconfig.json          # TypeScript configuration file
└── README.md              # Documentation for the project
```

## Getting Started

### Prerequisites
- Node.js and npm installed on your machine.
- A GitHub account for hosting the project on GitHub Pages.

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/MuriisaJohn/legalAI.git
   ```
2. Navigate to the project directory:
   ```
   cd legal-assistant
   ```
3. Install the dependencies:
   ```
   npm install
   ```

### Running the Application
To run the application locally, you can use a simple HTTP server. You can install `http-server` globally using npm:
```
npm install -g http-server
```
Then, navigate to the `docs` directory and start the server:
```
cd docs
http-server
```
Open your browser and go to `http://localhost:8080` to view the application.

### Deployment
The project is configured to deploy automatically to GitHub Pages using GitHub Actions. When you push changes to the main branch, the workflow defined in `.github/workflows/deploy.yml` will trigger and deploy the latest version of the application.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
