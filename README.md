# webScrapping

How to Use the App:

1. Clone the project.
2. Go to the directory where you cloned the app..
3. Run npm install.
4. Execute npm run start
5. You are going to see prompt asking: 'File name to store the scrapping result?'
6. Introduce the name of the file where the scrapping results are going to be saved.
7. Go to folder 'output' to see the file created with the results.
8. If you want to run tests execute npm test

🎯 The Project:
Web crawler using scraping techniques that extracts the first 30 entries from https://news.ycombinator.com/. And returns the title, the number of the order, the number of comments, and points for each entry.

And then perform a couple of filtering operations:

1. Filter all previous entries with more than five words in the title ordered by the number of comments first.
2. Filter all previous entries with less than or equal to five words in the title ordered by points.

🚀 Technologies Used:

JavaScript: Empowering interactive and dynamic web development, JavaScript is a versatile programming language that runs in web browsers, enabling enhanced user experiences and client-side functionality.

Lodash is a powerful JavaScript utility library known for its modular design and extensive set of functions. Widely embraced in functional programming, Lodash simplifies and optimizes common tasks, offering consistent and efficient solutions for array, object, and functional operations across diverse JavaScript environments.

ESLint: Ensuring code quality and consistency, ESLint is a pluggable linting utility for JavaScript that helps developers identify and fix potential issues, adhere to coding standards, and maintain a clean codebase.

Prettier: Streamlining code formatting, Prettier is an opinionated code formatter that ensures consistent styling across projects. It automates the process of code formatting, reducing bikeshedding and enhancing code readability.

Mocha: Simplifying JavaScript testing, Mocha is a flexible testing framework that runs on Node.js and in the browser. It provides a robust and feature-rich environment for writing and executing test suites, making it a popular choice for test-driven development.

Chai: Enhancing assertion libraries, Chai is a BDD/TDD assertion library for Node.js and browsers. It provides a clean and expressive syntax for making assertions in tests, promoting readability and ease of use in testing suites.

Inquirer: Facilitating interactive command-line interfaces, Inquirer is a powerful Node.js library for collecting user input through a series of prompts. It simplifies the process of creating interactive and user-friendly command-line applications.

Puppeteer: Automating browser tasks, Puppeteer is a Node library that provides a high-level API to control headless browsers or full browsers. Developed by Google, it is commonly used for web scraping, automated testing, and taking screenshots or generating PDFs of web pages.
