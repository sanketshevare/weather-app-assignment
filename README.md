# Weather Dashboard App

## Overview

This Weather Dashboard App is a React application designed to provide users with current weather information for multiple cities. It utilizes the OpenWeatherMap API to fetch weather data and displays it in a user-friendly interface.

## Setup

1. Clone the repository: `git clone https://github.com/yourusername/weather-dashboard-app.git`
2. Navigate to the project directory: `cd weather-dashboard-app`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`
5. Open your browser and visit `http://localhost:3000` to view the app.

## Configuration

To use the OpenWeatherMap API, you need to obtain an API key. Once you have the key, create a `.env` file in the root directory of the project and add the following line:



## Folder Structure

The project follows a standard React folder structure:

```
weather-dashboard-app/
│
├── src/
│   ├── components/        # React components
│   ├── pages/             # Page components
│   ├── redux/             # Redux store setup
│   ├── services/          # API service
│   ├── styles/            # CSS styles
│   └── utils/             # Utility functions
│
├── public/
│   └── index.html         # HTML template
│
└── README.md              # Project documentation
```

## Testing

Testing is implemented using Jest and React Testing Library. To run tests, use the command:

```
npm test
```

## Contributing

Contributions are welcome! Please follow the standard GitHub flow: Fork the repository, create a new branch for your feature or fix, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
