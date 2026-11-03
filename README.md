# StudyHub AKTU — CSE Portal

A polished responsive front-end portal for semester-wise AKTU B.Tech CSE study materials. Built with plain HTML, CSS and JavaScript; suitable for GitHub Pages.

## Included
- Semester selector for 1st through 8th semester
- Subject catalog with course codes/categories (sample catalog; verify your scheme)
- Search and filters for semester and resource type
- Notes / PYQ / Important Questions resource cards
- Mobile navigation and responsive layout

## Publish
1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, `script.js`, and the `materials` folder.
3. In **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/(root)`, then Save.
4. Use the GitHub Pages URL shown after deployment.

## Important: verify the syllabus
AKTU course structures and course codes can change by scheme, batch and academic year. The subject catalog is a starting template, not a certified official syllabus. Verify every semester's subjects and codes against the syllabus for your own batch before public use. Some entries are electives/practicals and may differ by specialization.

## Add PDFs
Create a PDF in `materials/`, then update the relevant resource-card action in `script.js` to open its relative path, or change the resource data model to include a `file` property. Use only material you have permission to share and provide attribution where needed.

This is a static front-end: it does not include student accounts, a database, or admin uploads.
