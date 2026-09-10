# Setup & Deployment Guide

## 1. Portfolio site

**Before deploying, edit `portfolio/index.html`:**
- Replace `github.com/yourusername`, `linkedin.com/in/yourusername`, and `your.email@example.com` in the Contact section with your real links.
- Once you build the two real projects, replace the two placeholder cards in the Projects section with real titles, descriptions, and links.

**Deploy (free, ~5 minutes):**
1. Create a GitHub repo (e.g. `parthib-portfolio`) and push this folder's contents to it.
2. Go to [vercel.com](https://vercel.com), sign in with GitHub, click "Add New Project," select the repo, and deploy — no build settings needed since it's plain HTML.
3. You'll get a live URL like `parthib-portfolio.vercel.app`. Add that link to Internshala, LinkedIn, and your resume.

*(Netlify works the same way if you prefer it — drag-and-drop the folder at app.netlify.com/drop for the fastest possible deploy.)*

## 2. Movie Search App

**Get your free API key:**
1. Go to https://www.omdbapi.com/apikey.aspx
2. Select the free tier, enter your email, and check your inbox — the key arrives instantly.
3. Open `movie-app/index.html`, find the line `const API_KEY = "YOUR_OMDB_API_KEY";` and paste your key in.

**Test it locally:** just open `index.html` in your browser and search for a movie.

**Deploy:** same steps as above — push to a new GitHub repo, deploy on Vercel.

⚠️ Note: this exposes the API key in client-side code, which is fine for OMDb's free tier and a portfolio project, but isn't a pattern to use for anything with a paid or rate-sensitive key in a real production app. Worth a one-line mention if an interviewer asks about it — it shows you understand the tradeoff.

## 3. Writing your GitHub READMEs

For each project's repo, add a short `README.md` with:
- One-sentence description of what it does
- Tech used (e.g. "HTML, CSS, JavaScript, OMDb API")
- Link to the live demo
- One thing you learned or a challenge you solved (recruiters and interviewers like this — it gives them something to ask about)

## 4. After both are live

- Add both live links + GitHub links to your Internshala profile's Projects section
- Add them to LinkedIn under the "Projects" section too
- Mention both briefly in your Internshala cover notes when relevant to the role (e.g. "built and deployed a movie search app integrating a third-party API")
