# Rivan Alamsyah — GitHub Profile README

## Files

- `README.md` — profile README.
- `assets/skills-marquee.gif` — locally hosted animated technology ticker. Put this in the root of the repository named `rivanalamsyah`.
- `.github/workflows/snake.yml` — generates the contribution snake SVGs and publishes them to the `output` branch.

## Setup

1. Open `https://github.com/rivanalamsyah/rivanalamsyah`.
2. Replace the repository's root `README.md` with this package's `README.md`.
3. Add `.github/workflows/snake.yml` at the exact path shown above.
4. Commit and push the changes to `main` (or `master`).
5. Open the repository's **Actions** tab and run **Generate contribution snake** using **Run workflow**.
6. If GitHub blocks the workflow from pushing, open **Settings → Actions → General → Workflow permissions**, select **Read and write permissions**, and save.
7. Run the workflow again. It will create/update the `output` branch with:
   - `github-contribution-grid-snake.svg`
   - `github-contribution-grid-snake-dark.svg`

The snake image in the README will appear after the first successful workflow run. The scheduled job refreshes it daily.

## Notes

- The README uses GitHub-supported Markdown/HTML elements and externally hosted SVG/image endpoints. It does not rely on embedded JavaScript or custom CSS.
- GitHub README does not support arbitrary hover handlers, React components, or interactive scripts. The expandable project groups use native `<details>` / `<summary>` elements.
- The project list outside the three CV-selected projects is retained from the previously supplied README and should be checked for publication accuracy.
- Confirm the professional experience dates before publishing: the supplied CV lists the current role as January–December 2026.
- Add repository or live-demo links to individual projects only after confirming their public URLs.
