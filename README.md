# Netflix Clone with MERN Stack


## Features
- User Authentication**: Register and log in with secure password hashing using JWT and Bcrypt.
- Browse Content**: Movies and TV shows are fetched from the TMDB API.
- Search Functionality**: Search for movies, TV shows, or actors.
- Responsive UI**: Fully responsive design optimized for all devices.
- Watch Movies/TV Shows**: Allows users to stream content via embedded links.
- Trending Content**: Dynamic content displayed on the home page based on trending movies/shows.
- Protected Routes**: Only logged-in users can access specific routes, e.g., viewing content or search history.

## Tech Stack
- Frontend: React, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB (MongoDB Atlas)
- Authentication: JWT (JSON Web Tokens)
- API: The Movie Database (TMDB) API
- State Management: React Hooks and Context API
- Other Tools: Axios, Bcryptjs, Mongoose


### Prerequisites

- **Node.js** 
- **npm** 
- **MongoDB** (Local or MongoDB Atlas for remote database)
- **TMDB API Key** (Register at [TMDB](https://www.themoviedb.org/))

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/netflix-clone.git
   cd netflix-clone

2. **Install dependencies for the backend:**
   ```bash
   npm install

3. **Install dependencies for the frontend:**
   ```bash
   npm install --prefix frontend

4. **Configure environment variables:**
   Create a .env file in the root directory with the following variables:
   ```bash
   MONGO_URI=mongodb+srv://yourMongoDBUser:yourMongoDBPassword@cluster0.mongodb.net/netflix_clone?retryWrites=true&w=majority
   PORT=5050
   JWT_SECRET=yourJWTSecret
   TMDB_API_KEY=yourTMDBApiKey
   NODE_ENV=development
   
5. **Run the application:**
   
   Development Mode:
   ```bash
   npm run dev
   ```

   Production Build:
   ```bash
   npm run build
   npm start

6. **Access the app:**
   Open **http://localhost:5055** in your browser for local development.


7. **GITHUB-URL:**
   open **https://github.com/Deejeshpatel/NETFLIX-CLONE.git** 

