# JavaScript Revision

Targeted revision of Jonas Schmedtmann's **The Complete JavaScript Course** before React.
On my first pass I watched these sections but wrote little or no code, so now I re-code them from clean starter files.

## Sections

- [ ] `11-arrays-bankist` Working With Arrays (Bankist app)
- [ ] `13-advanced-dom-bankist` Advanced DOM and Events (Bankist website)
- [ ] `14-oop` Object-Oriented Programming
- [ ] `15-mapty` Mapty app (OOP, geolocation, Leaflet)
- [ ] `16-async` Promises, async/await, AJAX
- [ ] `17-modules-tooling` ES modules, npm, Parcel, functional JS

Sections 1–10 and 12 are not part of this revision.

## Suggested order

11 → 16 → 17 first. These matter most for React: `map`, `filter`, `reduce`, `find`, `sort`, copies with spread, `fetch`, `async/await`, `try/catch`, `import/export`, npm.
Then 14 → 15 → 13. These matter less for React.

## How I revise

1. Read the lecture title. Try to write the code from memory first.
2. Watch the video only where I get stuck.
3. Compare with Jonas's `final` code only after my code works.
4. After each session, add an entry in `LEARNING_LOG.md`.

## Notes

- `16-async`: if the API in the video doesn't work, use the URLs in the comments at the top of `script.js`, or the one from the Udemy announcement: `https://countries-api-836d.onrender.com/countries/`
- `15-mapty`: geolocation needs a secure page. Open it with Live Server (localhost is fine). Add the Leaflet links to `index.html` when the lecture does.
- `17-modules-tooling`: run `npm init` / `npm install` here as in the lecture. `node_modules`, `dist` and `.parcel-cache` are ignored by Git.
- Starter files are clean copies from Jonas's repo (master branch). My first-pass code is still in `~/Courses/Jonas Schmedtmann/The Complete JavaScript Course/complete-javascript-course-master/<section>/starter`.

## Reference

- Course repo: https://github.com/jonasschmedtmann/complete-javascript-course
