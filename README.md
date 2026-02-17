# 🎬 Movie Finder Web App

A simple full-stack movie search application that allows users to search movies using the OMDb API, view detailed movie information, and save selected movies into database.

---

## 🚀 Features

- Search movies by title
- Fetch movie data from the OMDb API
- Display detailed movie information (poster, genre, director, actors, IMDb rating)
- Save selected movies into a MySQL database
- Prevent duplicate movie entries
- Smooth loading indicator and user-friendly UI

---

## 🧠 Project Workflow

This project follows a clear and logical workflow:

1. **User Input**  
   The user enters a movie name in the search box.

2. **API Request Handling**  
   The backend sends a request to the OMDb API using the provided movie name.

3. **Detailed Movie Fetching**  
   Each movie result is enriched with full details using its IMDb ID.

4. **Frontend Rendering**  
   The fetched movie data is dynamically displayed on the webpage.

5. **Data Persistence**  
   Selected movies can be saved into a MySQL database for future use.

---

## 🗄️ Database Overview

- Database name: `Movie_Database`
- Table: `movie_list`
- Automatically created if it does not exist
- Uses unique IMDb IDs to prevent duplicate entries

Stored data includes:
- IMDb ID
- Movie title
- Genre
- Director
- Actors
- Poster URL
- IMDb rating

---

## ⚙️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **API:** OMDb API
- **Database:** MySQL
- **Data Format:** JSON

---

## 📡 API Usage

This project uses the **OMDb API** to fetch movie data.

You must:
- Obtain your own API key from OMDb
- Insert the API key into the backend configuration

---

## 🔐 Important Notes

- This project is intended for **learning and practice purposes**
- The API key should not be exposed in production environments
- Local server setup (XAMPP / WAMP / LAMP) is required to run PHP and MySQL

---

## 📜 License

This project is licensed under the MIT License.  
Feel free to use, modify, and learn from it.

## 👤 Author

This project is made by Roshan Karki

---

