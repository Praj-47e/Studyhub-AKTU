# StudyHub AKTU

A responsive, static student study portal built with HTML, CSS and vanilla JavaScript. Ready for GitHub Pages.

## Preview locally
Open `index.html` in a browser. No build tools or backend are required.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `studyhub-aktu`.
2. Upload `index.html`, `style.css`, `script.js`, and this README. Keep all files in the repository root.
3. Open the repository **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to provide the published website link.

## Add real study materials
The current cards are examples, not real downloadable course files. To add a PDF:
1. Create a folder named `materials` in the repository.
2. Upload your PDF, such as `materials/dbms-unit-1.pdf`.
3. In `index.html`, find the matching card's `<a class="download-link ...">` and replace the placeholder anchor with:
   `<a class="download-link" href="materials/dbms-unit-1.pdf" target="_blank" rel="noopener">View material ↗</a>`
4. Update the sample title, description, semester, type, and search terms as needed.

Only upload materials you have permission to share. Add a small source/attribution note when appropriate.

## Customize
- Colors, spacing and layout: `style.css`
- Material cards and page content: `index.html`
- Search and filtering behavior: `script.js`

This is a static front-end demo. It does not include accounts, a database, or an admin upload panel.
