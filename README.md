# Oscar Nevarez · portfolio

A single-page portfolio for recruiters and hiring managers: areas of expertise, own projects, experience and resume.

- `index.html`: the whole site. Content lives in the `CONTENT` block at the top of the script
  (`AREAS`, `PROJECTS`, `JOBS`, `STACK`, `POSTS`, `LINKS`); the page renders from it. No build step.
- `resume.json`: the same facts in [JSON Resume](https://jsonresume.org/schema/) form for ATS tools and agents.
- `.nojekyll`: lets GitHub Pages serve the files as they are.

## Publish

GitHub Pages: Settings → Pages → Source "Deploy from a branch", branch `main`, folder `/ (root)`.
The site is then at `https://oscarnevarezleal.github.io/resume/`. To serve it from onevarez.com, add a
`CNAME` file with the domain and point the DNS at GitHub Pages.

## Edit

Open `index.html`, change the data block, commit. Keep `resume.json` in step with it.
Dates, education and earlier roles are not in the data yet; add them to `JOBS` and `resume.json`.
