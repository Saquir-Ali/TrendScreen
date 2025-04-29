🎬 Movie Trends App 🍿


Welcome to the Movie Trends App! 


🚀This vibrant React.js single-page app lets you browse blockbuster movies, search for your favorites, and discover what's trending based on user searches. Built with modern tools and a sprinkle of magic ✨, it’s fully responsive and ready to shine on any device. Let’s dive into the cinematic experience! 🎥

🌟 Features

Browse Movies 📽️: Explore popular movies powered by the TMDB API.
Smart Search 🔍: Find movies with a debounced search to keep things smooth.
Trending Vibes 🔥: See the top 5 movies users are buzzing about, tracked via Appwrite.
Sleek Design 🎨: Responsive UI styled with Tailwind CSS v4.0 for a polished look.
Fast Updates ⚡️: React’s Virtual DOM ensures seamless, no-reload interactions.
Error Handling 🛠️: Loading spinners and error messages for a flawless experience.
Ready to Deploy 🌍: Host it online with Hostinger and show off your creation!


🛠️ Technologies Used

React.js ⚛️: For building a dynamic, component-based UI.
Tailwind CSS v4.0 🎨: Utility-first CSS for stunning, responsive designs.
Vite 🚀: Lightning-fast build tool for dev and production.
Appwrite ☁️: Backend-as-a-service to track search trends.
TMDB API 🎬: Fetches movie data for endless cinematic fun.
React-Use 🧩: useDebounce hook for optimized search.
Node.js & npm 📦: Powers the backend and dependency management.
Git 🗃️: Version control to keep your code in check.
Hostinger 🌐: Hosting platform for deploying your app.


📋 Prerequisites
Before you start, grab these essentials:

Node.js (LTS) 🟢: Download from nodejs.org.
Git 🗂️: Get it at git-scm.com.
A code editor like VS Code or WebStorm ✍️.
Accounts for:
TMDB API 🎥: Sign up at themoviedb.org.
Appwrite ☁️: Create an account at appwrite.io.
Hostinger 🌍: Optional for deployment (Premium plan recommended).




🏗️ Installation

Clone or Create the Project 📂:
git clone https://github.com/your-username/movie-trends-app.git
cd movie-trends-app

Or start fresh with Vite:
npm create vite@latest movie-trends-app -- --template react
cd movie-trends-app


Install Dependencies 📦:
npm install


Set Up Tailwind CSS 🎨:
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init



Install Appwrite SDK ☁️:
npm install appwrite


Install React-Use 🧩:
npm install react-use


Configure Environment Variables 🔑:Create .env.local in the project root:
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id


Get VITE_TMDB_API_KEY from TMDB.
In Appwrite, create a project, database (movies), and collection (metrics) with attributes:
search_term (string, required, 1000 chars)
count (integer, default: 1)
poster_url (string, required)
movie_id (integer, required)


Copy IDs from Appwrite dashboard.


Add Assets 🖼️:

Download images from the Figma design (linked in the video description) or create your own:
hero.png: Hero banner.
hero-bg.jpg: Hero background.
logo.png: App logo.
no-movie.png: Placeholder for missing posters.
search.svg: Search icon.
star.svg: Rating star icon.


Place them in the public/ folder with proper names.




📂 Project Structure
movie-trends-app/
├── public/                 🌄 Static assets
│   ├── hero.png
│   ├── hero-bg.jpg
│   ├── logo.png
│   ├── no-movie.png
│   ├── search.svg
│   ├── star.svg
├── src/                    📜 Source code
│   ├── assets/             🖼️ Media assets
│   ├── components/         🧩 React components
│   │   ├── Search.jsx
│   │   ├── Spinner.jsx
│   │   ├── MovieCard.jsx
│   ├── appwrite.js         ☁️ Appwrite SDK setup
│   ├── App.jsx             🎬 Main app component
│   ├── main.jsx            🚪 Entry point
│   ├── index.css           🎨 Global styles
├── .env.local              🔑 Environment variables
├── .gitignore              🚫 Files to ignore
├── index.html              🌐 Main HTML file
├── package.json            📋 Project metadata
├── vite.config.js          ⚙️ Vite configuration
├── README.md               📝 You're reading it!


🚀 Running the App

Start the Dev Server 🌐:
npm run dev

Visit http://localhost:5173 to see the app in action! 🎉

Test It Out 🕹️:

Browse popular movies 📽️.
Search for favorites like "The Godfather" or "Avengers" 🔍.
Check the trending section for hot picks 🔥.




🌍 Deployment

Build for Production 🏭:
npm run build

This creates an optimized dist/ folder.

Deploy to Vercel 📡:


🎮 Usage

Home Page 🏠: A stunning hero section with a search bar and popular movies.
Search 🔎: Type a movie name to filter results (debounced for performance).
Trending Movies 🔥: Top 5 movies based on user searches, powered by Appwrite.
Movie Cards 🎟️: Showcases posters, titles, ratings, languages, and release years.


🤝 Contributing
Want to make this app even cooler? 🌟

Fork the repo 🍴.
Create a branch: git checkout -b feature/awesome-feature.
Commit changes: git commit -m "Add awesome feature".
Push: git push origin feature/awesome-feature.
Open a pull request 📬.

Please follow the project’s coding style and add tests where possible.

📚 Resources

TMDB API 🎥: themoviedb.org
Appwrite ☁️: appwrite.io
Tailwind CSS v4.0 🎨: tailwindcss.com
Vite 🚀: vitejs.dev
Figma Design 🖌️: Grab assets from the video description.
GitHub Repo 🗃️: Find the full code in the video description.
JS Mastery Pro 📚: More courses at jsmastery.pro.
Spinner ⏳: Free SVGs from loading.io.


📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

🎥 Built with passion and Love.

🌟 Star this repo if you love it!💻 Happy coding!


🚀This project is licensed under the MIT License. See the LICENSE file for details.
