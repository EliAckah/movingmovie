**Movie App**

**Overview**

This is a React-based movie search application with optimized searching functionality. It utilizes The Movie Database (TMDb) API to fetch movies and display trending movies. The app also features a debounced search to reduce unnecessary API calls and improve performance. Additionally, it integrates with Appwrite for tracking search counts.

**Features**

🔎 Search for Movies: Instantly find movies using TMDb API.

📊 Trending Movies: View the most popular movies.

⚡ Optimized Searching: Uses debouncing to minimize API calls and improve user experience.

⏳ Loading Indicators: Displays a spinner while fetching data.

📡 Error Handling: Handles API errors and network issues gracefully.



**Technologies Used**

React (Frontend framework)

Appwrite (Backend service for search tracking)

TMDb API (Movie database)

React Hooks (State management and side effects)

React Use (Debounce functionality)


**Installation**

Clone the repository:

git clone https://github.com/EliAckah/movingmovie.git
cd movingmovie

Install dependencies:

npm install

Set up environment variables:
Create a .env.local file in the root directory and add your TMDb API key:

VITE_TMDB_API_KEY=your_tmdb_api_key_here

**Start the development server:**

npm run dev

**Usage**

Type a movie name in the search bar to fetch results.

View trending movies in the "Trending Movies" section.

Click on any movie for more details.

Deployment

You can deploy this app using services like Vercel, Netlify, or Firebase Hosting.

Contributing

If you want to contribute:

Fork the repository.

Create a new branch: git checkout -b feature-name

Commit changes: git commit -m 'Add feature'

Push to branch: git push origin feature-name

Open a pull request.

License

This project is licensed under the MIT License.

Enjoy using the Movie App! 🍿🎬
