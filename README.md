# AI Finance Platform

Welcome to the **AI Finance Platform**! This platform aims to provide an intuitive financial management experience powered by AI. It includes features for account management, transaction tracking, financial analysis, and more.

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Technologies](#technologies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run the project locally, follow these steps:

git clone https://github.com/nikhildamre/Welth.git cd Welth

### 1. Clone the Repository
Clone this repo to your local machine using:


### 2. Install Dependencies
Make sure **Node.js** (>=16) is installed. Then install the required dependencies:

npm install --legacy-peer-deps


### 3. Set Up Environment Variables
Ensure you have the required `.env` file. If one isn't available, you can create a new `.env` file based on the project's documentation. Make sure to add any API keys or configuration values needed for the platform.

### 4. Run the Development Server
Start the local development server:

npm run dev

Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Features

- **Account Management**: Add, edit, and manage financial accounts.
- **Transaction Tracking**: Log, view, and categorize transactions.
- **AI Financial Insights**: Leverage AI to provide personalized financial recommendations.
- **Reports & Analytics**: Generate detailed reports to analyze your financial habits.

## Technologies

This project uses the following technologies:

- **Next.js** (React-based framework)
- **Prisma** (Database ORM)
- **Node.js**
- **React** (Frontend Library)
- **AI Models** (For financial predictions and recommendations)
- **TailwindCSS** (CSS framework)

## Usage

### 1. Run in Development Mode

npm run dev

This will start the app on `http://localhost:3000`.

### 2. Build for Production
To build the app for production:

npm run build npm run start


### 3. Migrate Database
Run Prisma migrations to set up your database:

npx prisma migrate dev


## Contributing

We welcome contributions! If you'd like to contribute to the project, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to your fork (`git push origin feature-branch`).
6. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
