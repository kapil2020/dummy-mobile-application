# dummy-mobile-application
A modern UI routing application

## GitHub Pages Deployment

A GitHub Actions workflow is included to automatically deploy the site whenever
you push to `main` or `work`. The workflow uploads the current directory and publishes
it as a GitHub Pages site.

The repository uses a simple landing page (`index.html`) that links to two demos:
`final_drum_gemini_demo_app.html` and `final_drum_seek_demo_app.html`. After pushing
your changes to GitHub:

1. Open the repository on GitHub and go to **Settings** > **Pages**.
2. Under **Source**, choose the branch you want to publish from (e.g., `main` or `work`) and the root directory.
3. Save the settings and GitHub Pages will serve the application. Navigate to the landing page and select a demo, or access the HTML files directly.
