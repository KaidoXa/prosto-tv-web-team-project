# Product Requirements Document: ProstoTV

## 1. Problem Statement

**Problem:** Our project is for those people who spend more time on searching and choosing the movie that watching it. 

**Goal:** Build Prosto-TV - website that will help to find an appropriate movie or series for everyone without excessive visual noise.

## 2. Users & Users Stories

**Users**: Our users are people who watch movies and series for different reasons: relaxing, spending free time with family or friends and dive into cinematography.

**Users stories:**

1. As a user, I want to be able to find details about particular movie, so that I can decide whether I'd like to watch it or not.

2. As a user, I want to be able to get best movies in specific genre, so that I can find a film of this category.

3. As a user, I want to get list of latest movies, so that I can watch some new releases.

4. As a user, I want to retrieve an actor's filmography, so that I can watch a movie with my favorite actor.

5. As a user, I want to find trending movies, so that I can keep up with the trends.

## 3. Functional requirements

1. The website provides a searching engine for finding movie by the name.

2. The website has filters for movie genre, year.

3. The website has sorting mechanism by the data, rating, runtime.

4. The website gives an additional info about the movie, if user needs it.

5. The website has an actors list, which provides info about their filmography.

## 4. Non-functional requirements

1. The website work's logic is consistent and valid.

2. The website interface provides accessibility and ergonomics.

3. The website is compatible with different devices, OS.

4. The development team must be able to identify, fix, and deploy a patch for a Severity-1 production bug within 4 hours.

## 5. Scope of product

**In-scope:** searching for the information about existing movies/series, actors.

**Out-of-scope:** possibility to watch movie/series or download it.


## 6. Roadmap

1. **Environment Setup**
   - Set up GitHub repository, branching strategy (`main` + feature branches), and pull request workflow.
   - Initialize the project, configure linters/formatting, and set up routing.
   - Configure TMDB API keys via environment variables (`.env`).

2. **Core MVP**
   - Implement base TMDB API client and image URL helpers.
   - Build reusable UI components (layout, header/footer, movie cards with fallback posters, loading states).
   - Develop the Home page displaying trending and popular movies.

3. **Search, Filters & Sorting**
   - Implement movie search by title (`/search/movie`) with debounced input.
   - Add filtering by genre, release year, and minimum rating (`/discover/movie`).
   - Add sorting options (popularity, rating, release date) and pagination.

4. **Details & Filmography Pages**
   - Build the Movie Details page (overview, runtime, rating, trailer embed, cast list, and similar movies).
   - Build the Actor Details page with biography and full filmography (`/person/{id}`).

5. **Deployment & QA**
   - Handle error states, empty search results, and responsive design across devices.
   - Add required TMDB attribution logo/disclaimer in the footer.
   - Deploy the production build (e.g., Vercel / Netlify) and perform final cross-browser testing.