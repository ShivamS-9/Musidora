# Musidora: Internet Music Database Project

## Overview

Musidora is a web-based platform designed to manage and explore music-related content. It allows users to browse information about artists, albums, and songs while offering features such as search functionality, rating, commenting, and creating personalized playlists. The project combines front-end, interactivity, and backend features to provide an engaging user experience.

---

## Features

### **User Interface**

Musidora features a visually appealing and responsive interface created using HTML and CSS. Key pages include:

- **Home Page:** Showcases top charts for artists, albums, and songs, providing users with quick access to popular content.
- **Artists Page:** Displays a list of artists, each linking to their respective albums.
- **Albums Page:** Showcases albums of a selected artist, with each album linking to its song list.
- **Songs Page:** Displays songs within a selected album, including their durations.
- **About Page:** Shares details about the website and its creators.
- **Navigation Bar:** A persistent navigation bar enables easy navigation between key pages.
- **Footer:** A consistent footer with additional links and information.

---

### **Interactivity**

Dynamic and interactive features enhance the user experience:

- **Navbar Hover Effects:** Highlights navigation links on hover for better usability.
- **Typing Effect:** Mimics a typing animation for headings or descriptions.
- **Search Functionality:** Allows users to search for tracks using the iTunes API, with options to filter results by criteria such as duration and explicit content.
- **Audio Previews:** Provides users the ability to play snippets of songs directly from search results.
- **Artist Spotlight:** Highlights a featured artist with animations, a review system, and a countdown timer for upcoming releases.

---

### **User Engagement**

To improve user engagement, Musidora includes features like:

- **Rating and Commenting:** Users can rate songs or albums and leave comments to express their opinions.
- **Personalized Playlists:** Allows users to create and manage playlists, with options to add and remove songs.

---

### **Backend Integration**

The backend is powered by Flask and SQL to manage and store user data:

- **Dynamic Pages:** Flask templates generate dynamic content, such as playlists and search results.
- **Database Persistence:** SQL is used to persist user data, ensuring playlists remain intact even after reloading the website.
- **Playlist Management:** Users can add songs to their playlists from the song pages and view or edit their playlists on a dedicated playlist page.
