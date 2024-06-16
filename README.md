# Weather Application

A responsive weather application built using React that fetches weather data from the OpenWeather API and displays it based on the user's input.

## Project Description

This project is a weather application that allows users to view the current weather information for their location and search for weather details in other cities.
The application features a responsive design, making it accessible on various devices, including desktops, tablets, and mobile phones.
It also includes dark mode functionality for a better user experience in low-light conditions.

## Interaction
Netlify Link: https://666eaa0930c660adb96b38bf--howisitin.netlify.app/

## Features

- Display current weather information based on user's input
- Responsive design for various devices (desktop, tablet, mobile)
- Dark mode and light mode toggle functionality
- Ability to display weather information for multiple locations
- Additional weather details such as humidity, wind speed, and weather description
- Graceful handling of API responses and errors

## Technologies Used

- HTML: For the structure of the application
- CSS: For styling the application
- JavaScript (React): For building the user interface
- OpenWeather API: For fetching weather data

## Usage

1. Searching for Weather in Another City

    - Enter a city name or zip code in the input field and click the "Get Weather" button.
    - The application will fetch and display the current weather information for the entered location.

2. Dark Mode Toggle

    - Click the "Toggle Dark Mode" button to switch between light and dark modes.

## Dark Mode Toggle

The application includes a dark mode toggle functionality.
When the button is clicked, the application switches between light and dark modes, enhancing the user experience in different lighting conditions.

##Limitations

The Application runs as per the requirements of user(light mode or dark mode) which fetches the data of different weather conditions of different cities based on city name or zip code.. the application stores the data of the previous searches in the UI. but when an error occurs while fetching the data(only possible way due to incorrect city name or zip code entered), the application doesn't show the previous results.

