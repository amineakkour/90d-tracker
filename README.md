# 90d-tracker

90days tracker is a single-page application built using Vite React, designed to help users track their daily experiences over 90 days. The app allows users to mark each day as either good or bad, providing insights into their overall well-being and progress over time.

## Features

- **Daily Status Tracking**: Users can specify whether their day was good or not by clicking on the highlighted box representing the current day.
  
- **Day Status Setting**: After selecting the current day, a popup window appears, allowing users to set the status of their day.

- **Local Storage**: Data is stored locally using the browser's localStorage API, ensuring that user progress is saved even after closing the application.

- **Limited Day Editing**: Users can only set the status of the current day and cannot edit previous days, maintaining the integrity of the tracking process.

- **Status Summary**: The app provides a summary of the user's progress, including the number of good and bad days, as well as the number of days that have passed.

- **Reset Functionality**: A button in the header allows users to delete all stored status data, providing a clean slate for starting a new tracking period.

## Usage

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Run the development server with `npm run dev`.
4. Access the application in your browser at the specified localhost address.

## Technologies Used

- Vite
- React
- JavaScript
- HTML5
- CSS

## Author

AKKOUR Mohamed Amine
