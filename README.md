## Todo List App

This is a simple Todo List web application built using HTML, CSS, JavaScript, AJAX, Node.js, Express, and MongoDB. The app allows users to create and manage their to-do lists, add tasks to each list, and customize tasks with due dates, checklists, and labels.

### Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

### Features

- Create and manage multiple to-do lists.
- Add tasks to each list.
- Customize tasks with due dates, checklists, and labels.
- Store data in MongoDB for persistent storage.
- User-friendly interface with a clean and intuitive design.

Feel free to explore and add more features to enhance the functionality of the app.

### Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-list-app.git

2. Navigate to the project directory:

cd todo-list-app

3. Install dependencies:
npm install

4. Configure MongoDB:

--Make sure MongoDB is running.
--Update the MongoDB connection string in config/db.js if necessary.

## Usage
1.Start the application:
-npm start
2 .Open your browser and visit http://localhost:8000.

3.Start creating and managing your to-do lists!

## Project Structure

todo-list-app/
|-- config/
|   |-- db.js            # MongoDB configuration
|-- public/
|   |-- styles/
|       |-- style.css     # Custom styles
|-- views/
|   |-- layouts/
|       |-- main.ejs      # Main layout template
|   |-- partials/
|       |-- header.ejs    # Header partial
|   |-- index.ejs         # Main view
|-- .gitignore            # Git ignore file
|-- app.js                # Express application setup
|-- package.json          # Node.js project file
|-- README.md             # Project documentation

## Technologies Used

- HTML, CSS, JavaScript for the frontend
- AJAX for asynchronous communication with the server
- Node.js and Express for server-side development
- MongoDB for data storage
- EJS (Embedded JavaScript) for templating

## Contributing
Contributions are welcome! Feel free to fork the project and submit pull requests to add new features or fix issues.

## License
This project is licensed under the MIT License.