# Skyrim Creation Kit: first steps

A five-lesson interactive how-to. It is a static site: `index.html` plus a `media` folder. No build step.

## Publish on GitHub Pages
1. Create a new repository on GitHub.
2. Upload everything in this folder (`index.html`, `media/`, `.nojekyll`) to the repository root.
3. Open Settings, then Pages. Under Build and deployment, choose "Deploy from a branch", pick `main` and `/ (root)`, then Save.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Test locally
Run `python3 -m http.server` in this folder and open http://localhost:8000.
Opening `index.html` by double-click also works, though some browsers limit video then.

## Editing lessons
Lesson titles, steps, chapter timestamps and quiz questions are in the `LESSONS` list near the bottom of `index.html`. Times are in seconds. Videos and screenshots live in `media/`.

Progress is saved in each visitor's own browser.
