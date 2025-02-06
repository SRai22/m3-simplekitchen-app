# m3-simplekitchen-app
Web-602-Spring 2025 : A web application for managing kitchen recipes and user registrations.

## Features
- User Registration System
- Recipe Display
- Admin Authentication
- Responsive Design
- MongoDB Integration
- SCSS/CSS Styling

## Technologies Used
- Node.js
- Express.js
- MongoDB/Mongoose
- Pug Template Engine
- SCSS for styling
- HTTP Basic Authentication

## Installation

1. Clone the repository:
```bash
git clone https://github.com/SRai22/m3-simplekitchen-app.git
cd m3-simplekitchen-app
```

2. Install dependencies:
```bash
npm install 
```

3. Create a .env file in the root directory: 
```bash
DATABASE=mongodb://localhost:27017/simplekitchen
```

4. Start MongoDB as per the instructions. For Ubuntu:
```bash
sudo systemctl start mongod
```

## Usage 
```bash
npm run watch:all
``` 

This will:

Start the Node.js server with nodemon
Watch for SCSS changes and compile to CSS
Run parallel processes for development
The application will be available at http://localhost:3000 

## Project Structure
```bash
m3-simplekitchen-app/
├── models/
│   └── Registration.js
├── public/
│   ├── scss/
│   │   ├── styles.scss
│   │   └── nav.scss
│   └── css/
├── routes/
│   └── index.js
├── views/
│   ├── index.pug
│   └── layout.pug
├── app.js
├── start.js
└── package.json 
```


## Available Scripts
* npm run scss: Compile SCSS to CSS
* npm run watch:scss: Watch SCSS files for changes
* npm start: Start the application with nodemon
* npm run watch:all: Run all watch processes simultaneously

