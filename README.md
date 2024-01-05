# GitHub Account Finder

## Overview

GitHub Account Finder is a simple React application that allows users to search for GitHub accounts based on usernames or email addresses. It leverages the GitHub API to retrieve relevant user information and displays the results in a clean and user-friendly interface.

## Features

- **User Input:** Users can input a GitHub username or email in the search field.
- **Search:** Clicking the "Search" button initiates the search for GitHub accounts based on the entered query.
- **Results Display:** The app displays user cards for each matching GitHub account, showing the user's avatar, GitHub profile link, and username.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- CSS: Styling the components for a visually appealing and responsive design.
- GitHub API: Utilized for fetching GitHub account information based on user input.

## Setup Instructions

1. Clone the repository to your local machine.
2. Install dependencies using `npm install`.
3. Run the application with `npm start`.

## Usage

1. Open the application in your web browser.
2. Enter a GitHub username or email in the search input field.
3. Click the "Search" button to retrieve and display matching GitHub accounts.
4. View the results in the user card format, showcasing avatar, profile link, and username.

## Code Structure

- **`App.js`:** Main component containing the application logic and structure.
- **`user-card` Folder:** Contains the `UserCard` component responsible for displaying individual GitHub user information.
- **`App.css`:** Stylesheet for styling the components.

## How it Works

1. **Input Handling:** User input is captured using the `handleOnChange` function, updating the `inputValue` state.
2. **Search Trigger:** Clicking the "Search" button triggers the `onSearchSubmit` function.
3. **API Call:** The app makes an asynchronous API call to the GitHub API to find matching accounts based on the user's input.
4. **Results Display:** The retrieved results are displayed in user cards using the `UserCard` component.

## Credits

- This project was created by Sharad Singh Kushwaha.
- GitHub API documentation: [GitHub API](https://developer.github.com/v3/)
