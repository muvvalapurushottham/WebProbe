# WebProbe

The WebProbe Performance tool is a highly effective instrument designed to streamline the evaluation of web application performance, store crucial data, and validate URLs. In today's digital landscape, optimizing web performance is of utmost importance, and this tool empowers developers, testers, and website owners to effortlessly obtain insights into their websites' performance metrics. 

## Tools Used

### Performance Report Generation
The core functionality of this tool leverages Lighthouse, an open-source automated tool for improving the quality of web pages. By integrating Lighthouse, our project enables users to generate detailed performance reports for web pages. These reports encompass various aspects such as performance, accessibility, best practices, and SEO. Users can quickly identify areas for improvement and take action to enhance their web applications.

### Local and Session Storage
Our tool provides seamless integration with local and session storage mechanisms. Users can store essential data locally, ensuring the persistence of critical session information across page reloads or browser sessions. This feature is invaluable for applications requiring user state retention, shopping carts, or any scenario where temporary data storage is necessary. It also allows the user to customize the search for local storage and session storage.

### URL Validity Checker
To maintain data accuracy and avoid errors, our project offers a URL validity checker. Users can verify the correctness of URLs, safeguarding against broken links or incorrect inputs. This functionality ensures the accuracy of the generated reports and data integrity. Additionally, it allows users to schedule automatic URL checks at specified intervals. If a URL is found to be down, an email notification is sent to the admin.

## Table of Contents
- Installation
- Usage
- Contributing
- License

## Installation
To install this project, follow these steps:

1. Clone the repository.
2. Run `npm install` to install dependencies.

## Usage
To use this project, follow the steps below:

1. Start the terminal.
2. Start the node server by using: `node app.js`.
3. Open the `main.html` page with a live server.
4. Start the XAMPP server for the database (sudo /opt/lampp/./manager-linux-x64.run) to open the database -- http://localhost/phpmyadmin/

NOTE: No customized changes are required.

## Contributing
Thank you for considering contributing to our project! We welcome contributions from the community. To ensure a positive and productive experience, please follow these guidelines:

### Prerequisites
Before getting started, ensure you have the following prerequisites:

- Node.js (v18 or higher)
- Git

### Setting Up the Development Environment
1. Fork the repository to your GitHub account.
2. Clone your forked repository locally: `git clone <repository-url>`
3. Install project dependencies: `npm install`

### Contributing Code
1. Create a new feature branch for your changes: `git checkout -b feature/your-feature-name`
2. Make your changes, following our coding guidelines.
3. Ensure tests pass: `npm test`
4. Commit your changes: `git commit -m "Add your commit message"`
5. Push your changes to your forked repository: `git push origin feature/your-feature-name`
6. Submit a pull request to our main branch.

### Before Running Code
1. Check for the **put your email here** and **put your elastic email password here** replace with your elastic email logins .
2.