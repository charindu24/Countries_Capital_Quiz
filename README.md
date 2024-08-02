# Countries Capital Quiz

Welcome to the Countries Capital Quiz! This web application challenges users to identify the capital cities of various countries. It is built with Node.js, Express, and PostgreSQL.

## Features

- **Random Questions:** Each time you start the quiz, you get a new set of questions with random countries and their capitals.
- **Score Tracking:** The quiz keeps track of the number of correct answers.
- **User Interface:** A simple and intuitive UI with real-time feedback on your answers.

## Technologies Used

- **Backend:** Node.js with Express
- **Database:** PostgreSQL
- **Frontend:** HTML, CSS, EJS (Embedded JavaScript Templates)
- **Others:** Body-parser for handling form submissions

## Setup and Installation

Follow these steps to set up and run the project:

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/charindu24/Countries_Capital_Quiz.git
cd Countries_Capital_Quiz

2.Database details

Created database used pgAdmin

create database
CREATE DATABASE World;


create these tables
psql -U postgres -d World




Create the capitals table and insert data. You can use the following SQL commands as an example:

CREATE TABLE capitals (
  id SERIAL PRIMARY KEY,
  country VARCHAR(100) NOT NULL,
  capital VARCHAR(100) NOT NULL
);

INSERT INTO capitals (country, capital) VALUES
('France', 'Paris'),
('Germany', 'Berlin'),
('Italy', 'Rome'),
('Japan', 'Tokyo');


3.Install Dependencies
Ensure you have Node.js and npm installed.

Install the required Node.js packages:

npm install

. Configure the Application
Update the database configuration in index.js with your PostgreSQL credentials:
const db = new pg.Client({
  user: "your-username",
  host: "localhost",
  database: "World",
  password: "your-password",
  port: 5432,
});




4.### Instructions for Use

1. **Clone and Navigate:** Follow the steps to clone the repository and navigate to the project directory.
2. **Database Setup:** Create and configure your database, including schema and data.
3. **Install Dependencies:** Install Node.js dependencies.
4. **Configuration:** Update configuration files with your database credentials.
5. **Start Application:** Run the application locally and access it via a web browser.
6. **Packaging and Deployment:** Package the application as needed and deploy it to a hosting service.

This `README.md` should give users clear instructions for setting up, running, and deploying your Countries Capital Quiz application.


