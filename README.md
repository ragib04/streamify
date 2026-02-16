# Streamify – Video Streaming Platform

This project is a video streaming platform inspired by popular video-sharing applications. It is built using modern front-end technologies, including React, Redux Toolkit, TailwindCSS, and other libraries.

For the UI layer, I am using Tailwind CSS for styling.

Why Tailwind?
> It is a modern utility-first CSS framework that allows faster development and helps build clean and responsive interfaces efficiently.

I am using Redux Toolkit for Data management across the application.

React Router DOM is used for client-side routing.

Jest and React Testing Library are used for testing.

📌 Video content and metadata are powered by the YouTube Data API, used in compliance with YouTube’s Terms of Service.

## Features

Streamify Platform:
The project replicates the core UI design and functionalities of a modern video streaming platform.

Video List:
The app displays a paginated list of videos fetched from the YouTube API. The list supports lazy loading to enhance performance.

Video Preview & Playback:
Clicking on a video opens a preview page that displays the selected video using the official YouTube embedded player, along with basic details such as title, description, and view count.

Search Suggestions:
As the user types in the search bar, the app displays a dropdown list of suggested search queries, improving usability and discoverability.

Search Caching:
To improve performance and reduce unnecessary API calls, the app caches results of previous searches using Redux.

Optimized Search Using Caching and Debouncing:
The app uses debouncing to prevent API calls on every keystroke and combines it with caching for faster responses.

Optimized API Calls Using Debouncing:
Debouncing is applied across the app to optimize API usage, especially during scrolling and searching.

Comments Section:
The app includes a comments section that displays threaded comments fetched from the YouTube API for better readability.

Live Chat (API Polling):
A live chat feature fetches and updates messages continuously using API polling, simulating real-time interaction.

React Memo for Optimization:
The app uses React.memo() to prevent unnecessary re-renders and improve performance.

## Usage

To use this project, follow these steps:

1. Clone the repository.
2. Install the dependencies using `npm install`.
3. Start the development server using `npm start`.
4. Open your web browser and navigate to `http://localhost:3000`.

## Conclusion

This project demonstrates how to build a modern web application using React, Redux Toolkit, TailwindCSS, and other libraries. The project includes several useful features, such as search suggestions, search caching, optimized search using debouncing and caching, optimized API calls using debouncing, comments section, and live chat. These features are not only useful for a video streaming platform but can be applied to any large-scale web application. The project can be used as a starting point for building similar web applications and as a reference for learning how to implement advanced features in React.

## Dependencies

This project uses the following dependencies:

- React
- Redux Toolkit
- React Router DOM
- TailwindCSS

These dependencies are listed in the `package.json`


