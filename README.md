# FreeToGame API Integration

Welcome to my web app! This is one of my first projects as a beginner developer, and I’m excited to share what I’ve been building. I’m using the **FreeToGame API** to create an app that showcases some of the best free-to-play games available.

The goal of this project is to learn more about working with APIs, handling JSON data, and building user-friendly web apps while exploring the amazing world of free-to-play gaming.

---

## **About the FreeToGame API**

The **FreeToGame API** is a free, open-access API that provides data about hundreds of free-to-play games. With this API, I can retrieve information about games, including:

- Titles
- Genres
- Descriptions
- Platforms (PC, Browser, etc.)
- Developers and Publishers
- Release Dates

The API is completely free to use and requires no authentication, making it perfect for beginner developers like me to practice and build something exciting.

---

## **What My App Will Do**

Using the data from the FreeToGame API, my app will:

1. **List Popular Free-to-Play Games**: Display a searchable and filterable list of games.
2. **Game Details Page**: Show detailed information about individual games when selected.
3. **Filter Options**: Allow users to filter games by platform, genre, or popularity.
4. **Sort Features**: Enable sorting by release date, alphabetical order, or relevance.

---

## **API Endpoints Used**

Here are the main API endpoints I’ll be using in this project:

1. **Get All Games**  
   URL: `https://www.freetogame.com/api/games`  
   Fetches a list of all free-to-play games.

2. **Get Game Details**  
   URL: `https://www.freetogame.com/api/game?id={game_id}`  
   Retrieves details for a specific game by its ID.

3. **Filter Games by Platform**  
   URL: `https://www.freetogame.com/api/games?platform={platform_name}`  
   Example: Fetching all PC games.

4. **Filter Games by Genre**  
   URL: `https://www.freetogame.com/api/games?category={category_name}`  
   Example: Fetching all "Shooter" games.

5. **Sort Games**  
   URL: `https://www.freetogame.com/api/games?sort-by={sort_name}`  
   Example: Sorting games alphabetically or by release date.

---

## **What’s Next**

As I continue building, I’ll focus on:

- Improving the UI to make the app easy to navigate.
- Adding more advanced filters for users to find games tailored to their preferences.
- Experimenting with JavaScript frameworks to enhance the interactivity of the app.

---

## **Why I Chose This API**

The FreeToGame API is beginner-friendly, free, and offers great data for building a gaming-related project. It also helps me practice working with JSON responses, handling HTTP requests, and integrating API data into a web app.

---

Feel free to check out my app as it evolves, and thanks for supporting me on my developer journey!
