# Carrie Jiaqi Wang academic website

The current website is a responsive, static academic portfolio at https://carriejiaqiwang.github.io/.

## Content

- `index.html`: introduction, research overview, and personal interests.
- `research/index.html`: research directions, publications, preprints, and talks.
- `teaching/index.html`: teaching approach, verified course experience, and instructor development.
- `service/index.html`: graduate mentoring, academic service, and STEM outreach.
- `cv/index.html`: print-friendly public CV.
- `assets/site.css`: shared typography, layout, responsive behavior, and print styles.
- `images/ORIE2.png`: the existing portrait.

Update these HTML files directly. The CV and research page share publication information; keep both current. The public CV includes professional email but omits the personal phone number from the working CV.

## Local preview

From this repository, run `python3 -m http.server 8765`, then open http://localhost:8765/. No package installation or build step is required.

## Publishing

Publish the repository's `master` branch from its root through GitHub Pages. The `.nojekyll` file makes GitHub serve the static pages directly. The previous Jekyll theme files remain in the repository for reference and recovery; they no longer generate the current site.

The previous `/about/`, `/publications/`, `/talks/`, and `/cv-json/` addresses redirect to the updated destinations. `sitemap.xml` lists the current pages. When adding pages, update the navigation and sitemap.

Before publishing, check the five pages on a narrow and wide screen, verify paper links and publication status, and use the CV's print layout if exporting a PDF.

## Attribution

The repository originally used [Academic Pages](https://academicpages.github.io/), based on the Minimal Mistakes Jekyll theme. The original license and source files are retained. The October 2026 portfolio uses new static HTML and CSS.
