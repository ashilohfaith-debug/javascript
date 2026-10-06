# 30-Day Build-First JavaScript Roadmap

A project-driven path from JavaScript basics to a deployed full-stack app in 30 days, designed around **1 hour per day**, with extra-time options for days when you can go deeper.

The spine: **JS → DOM → APIs → React → Node/Express → Database → Deploy**

---

## The Addiction Engine (use these every day)

1. **Ship a project every 3 to 4 days.** Small wins drive the dopamine loop. Everything gets deployed.
2. **Never end a day on a broken screen.** Stop at a point where the next step is obvious. Write "Tomorrow: ___" in your README. You'll want to start the next day.
3. **Streak tracker.** Your GitHub contribution graph is the scoreboard. Commit daily, even tiny commits.
4. **Boss levels.** Each week ends with a boss project that uses everything from the week, built *without a tutorial*.
5. **Break it on purpose.** After a project works, add one feature nobody asked for. That's where real skill grows.
6. **Build in public.** Post a screenshot or demo link on LinkedIn/X each week. A little accountability goes a long way.
7. **Keep a "Wins" file.** Every day, write one line: "Today I built ___ without help."

## The 1-Hour Daily Template

| Time | What |
|---|---|
| 10 min | Learn: read or watch ONE small concept |
| 40 min | Build: apply it immediately in a project |
| 10 min | Commit, push, write today's win and tomorrow's first step |

**Rule:** if you're stuck for more than 25 minutes, look at docs or ask an AI to *explain* the concept, not write the solution.

---

## WEEK 1: Make Things Move (JS + DOM)

**Boss: a deployed mini-app collection**

| Day | Do | Build |
|---|---|---|
| 1 | Set up VS Code, Git, GitHub, and the terminal. Learn variables, types, and functions | Repo `30-day-js` with a "Hello" page, deployed on GitHub Pages |
| 2 | Conditionals, loops, arrays, objects | Number guessing game (console) |
| 3 | Array methods (`map`, `filter`, `reduce`) and scope | Mini text analyzer: counts words and finds the longest word |
| 4 | DOM selection and manipulation | Rock Paper Scissors with a UI |
| 5 | Events and event listeners | Etch-a-Sketch grid |
| 6 | Forms, validation, and `localStorage` | Todo app with persistence |
| 7 | **BOSS:** Calculator, no tutorial | Add keyboard support and a history panel |

## WEEK 2: Talk to the Internet (Async + APIs)

**Boss: Weather app**

| Day | Do | Build |
|---|---|---|
| 8 | ES6+: destructuring, spread, template literals, modules | Refactor a Week 1 project into modules |
| 9 | JSON, `fetch()`, Promises | Random joke or quote generator |
| 10 | `async/await` and error handling | Add loading and error states to it |
| 11 | Working with a real API (free, no key) | Pokédex search |
| 12 | Closures, higher-order functions, classes | Library app (add, delete, read/unread) |
| 13 | Search, filter, and sort | Add search and filter to the Library app |
| 14 | **BOSS:** Weather app (city search, current conditions, errors, responsive) | Deploy it, add a 5-day forecast |

## WEEK 3: React

**Boss: Movie/TV Explorer**

| Day | Do | Build |
|---|---|---|
| 15 | Why React, Vite setup, components, JSX, props | Profile card components |
| 16 | `useState` and events | Counter, then a todo list in React |
| 17 | Lists, keys, conditional rendering, forms | Notes app |
| 18 | `useEffect` and fetching data | Display popular movies from an API |
| 19 | Search plus loading and error states | Movie search |
| 20 | Routing (React Router) | Movie details page |
| 21 | **BOSS:** Favorites (localStorage), responsive polish | Deploy to Vercel or Netlify |

## WEEK 4: Backend + Database + Launch

**Boss: Job Application Tracker, full-stack**

| Day | Do | Build |
|---|---|---|
| 22 | Node basics, npm, and how HTTP works | A tiny server that returns JSON |
| 23 | Express: routes, middleware, status codes | REST API with in-memory data |
| 24 | SQL basics: SELECT, WHERE, INSERT, UPDATE, DELETE | Practice in the browser (SQLBolt) |
| 25 | JOINs, primary and foreign keys, and connecting Postgres to Node | API now saves to a real database |
| 26 | Connect React to your API (CORS, fetch) | Frontend lists, adds, and deletes applications |
| 27 | Edit and filter by status, plus dashboard counts | Applied / Interview / Offer / Rejected stats |
| 28 | Environment variables, validation, error handling | Harden the API |
| 29 | Deploy backend and database, then connect the live frontend | Live full-stack app |
| 30 | **LAUNCH DAY:** README, screenshots, demo link, post it | Portfolio entry for all 4 key projects |

**If you're short on time:** simple login (hashed passwords + JWT) is the first thing to add *after* Day 30, not squeezed in.

---

## Extra-Time Menu (days when you have 2+ hours)

Pick from the menu matching your current week.

### Week 1 extras
- Do 3 to 5 days of **JavaScript30** (Wes Bos): 30 small, fun projects
- Recreate a site you love using only HTML/CSS/JS
- Solve 5 easy problems on Exercism or Codewars

### Week 2 extras
- Build a **GitHub Profile Finder** using the GitHub API
- Make a **Typing speed test** or **Memory card game**
- Read about the event loop. Search "Jake Archibald event loop" and "What the heck is the event loop anyway?"

### Week 3 extras
- Add dark mode with `useContext`
- Build a **Kanban board** with drag and drop
- Rebuild the Weather app in React (a great skills check)
- Learn custom hooks (`useFetch`, `useLocalStorage`)

### Week 4 extras
- Add **JWT authentication** (register/login/protected routes)
- Add pagination and an "applications over time" chart
- Add **TypeScript** to a small project
- Write your first tests (Vitest/Jest)

### Always-available explorations
- Read other people's code on GitHub
- Browse the "Awesome JavaScript" lists
- Watch conference talks or Fireship's "100 Seconds" videos for fun
- Join a hackathon. It's the ultimate "build under pressure" practice and the best use of your skills.

---

## Resources

### Primary (pick ONE to follow, use the others to look things up)
- **The Odin Project** (theodinproject.com): structured, project-based, free
- **javascript.info**: the best free JS reference, written like a book
- **MDN Web Docs** (developer.mozilla.org): the official reference. Google "mdn + topic"

### JavaScript practice
- **JavaScript30** (javascript30.com): 30 projects in 30 days, free
- **Exercism** (JS track): small exercises with mentor-style feedback
- **freeCodeCamp**: the JS Algorithms & Data Structures course

### React
- **react.dev**: the official docs and tutorial are excellent now
- **Scrimba's Learn React**: interactive and beginner-friendly
- **Codevolution** or **Net Ninja** on YouTube for playlists

### Backend and databases
- **SQLBolt**: free interactive SQL lessons
- **PG Exercises** (pgexercises.com): practice real Postgres queries
- **Express docs** and **Node docs**
- **Neon** or **Supabase**: free-tier hosted Postgres

### Project ideas and APIs
- **public-apis** repo on GitHub: huge list of free APIs
- **Frontend Mentor**: real design challenges to build
- **roadmap.sh** (JavaScript and Full Stack): a visual map of where you are

### Deployment
- GitHub Pages, Netlify, Vercel (frontend)
- Render or Railway (backend; free tiers vary, so check current limits)

### Short, entertaining YouTube
- Fireship, Web Dev Simplified, Traversy Media, Kevin Powell (CSS)

---

## The 3 Rules

1. **Build first, then read.** Try the project, hit a wall, then learn the missing concept.
2. **One resource at a time.** Tutorial-hopping feels productive but isn't.
3. **Ship ugly.** A deployed project beats a perfect one on your laptop.

---

## Where You'll Be on Day 30

About 15 small projects and 4 portfolio-worthy ones: **Weather app**, **Library app**, **Movie Explorer**, and the full-stack **Job Tracker**. You'll be able to take an idea and break it into components, endpoints, and tables.
