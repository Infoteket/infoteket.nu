# infoteket.nu

Minimal Jekyll-based GitHub Pages site for Infoteket.

## Local development

You can preview the site locally (requires Ruby and Bundler):

1. Install dependencies:
	```bash
	bundle install
	```
2. Serve locally:
	```bash
	bundle exec jekyll serve
	```
3. Open http://localhost:4000

## Deployment

Pushing to `main` triggers the GitHub Actions workflow in `.github/workflows/jekyll-gh-pages.yml` which builds and deploys the site to GitHub Pages.

## Contact

info@infoteket.nu
