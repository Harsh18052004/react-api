# Delicous

**Delicous** is a React-based web application that displays a dynamic food menu catalogue. It fetches data from a public API to display the menu items, including details such as dish name, price, and description. 

## Features

- **Dynamic Menu**: The menu items are fetched using the Fetch API from an external data source, ensuring up-to-date content.
- **React Hooks**: The application uses React's functional components along with hooks like `useState` and `useEffect`.
- **Responsive Design**: The UI is designed to be mobile-friendly and responsive to various screen sizes.
- **Simple, User-Friendly UI**: Clean layout with a focus on readability and ease of navigation.

## Demo

You can view the project live at: https://vercel.com/harshs-projects-8df0d664/react-api

## Technologies Used

- **React**: For building user interfaces.
- **Fetch API**: For fetching menu data from a backend or public API.
- **CSS**: For styling the components.
- **React Router**: (Optional) For navigating between different sections of the app, if applicable.

## Installation

1. Clone the repository: git@github.com:HarshBti/react-api.git
2. Navigate to repository : cd react-api
3. Install the dependencies: npm install
4. Start the development server:npm start

## How it Works
1. The app uses the Fetch API inside a useEffect hook to retrieve the list of food items from an external API once the component mounts.
2. Each menu item is displayed with its name, price, and a short description.
3. The UI is designed with simplicity in mind to ensure ease of use for customers browsing the menu.


