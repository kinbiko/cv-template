# CV

Opinionated CV generator based on an easy-to-maintain Markdown document.

## Usage

- Create a new repository based on this repository template.
- Edit `cv.md`, ensuring no `*_HERE` text remains.
- Create a new tag with `git tag "$(date '+%Y-%m-%d')"` (or replace with your own version naming convention).
- Push the tag to GitHub and trigger the GitHub Actions `Generate CV as PDF` workflow with `git push --tags`

The [most recent tag](../../releases) will then contain the generated PDF after the workflow finishes executing.
