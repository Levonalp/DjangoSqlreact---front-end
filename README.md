# Pet photo App

## Introduction

This React application is designed to manage a list of dogs, providing functionalities such as fetching, creating, updating, and deleting dog entries. The application interacts with an external API to perform these operations.
.....
## Installation

To set up this project locally, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install all the necessary dependencies.
4. Once the dependencies are installed, you can start the application by running `npm start`.

## Features

### Dog Fetching

- Fetches dog data from an external API.
- Uses `axios` for API calls.
- Displays a loading spinner while data is being fetched.

### Dog Creation

- Allows the creation of new dog entries through a form.
- Submits new dog data to the API.

### Dog Deletion

- Provides the ability to delete dog entries.
- Uses a confirmation dialog before deletion.

### Dog Update

- Enables editing existing dog entries.
- Submits updated data to the API.

### Search Functionality

- Implements a search feature to filter dogs based on various attributes like name, breed, size, and color.

### User Interface

- Includes components like `Navbar`, `Dog`, and `Footer`.
- Utilizes `react-confirm-alert` for confirmation dialogs.
- Implements `react-loader-spinner` for loading indicators.

## Usage

After starting the application, you can perform operations like creating, updating, and deleting dog entries. The main page displays all the dogs fetched from the API, and you can use the search bar in the navbar to filter the dogs.

## Dependencies

- React
- axios
- react-confirm-alert
- react-loader-spinner

---

For more information on how to use each feature, please refer to the comments in the source code. Enjoy managing your dog database!
