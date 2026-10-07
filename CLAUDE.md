# Reading Tracker roadmap page

Public, read-only roadmap page for the Reading Tracker app, served by GitHub Pages from `main` (root folder).
Owner: Tobi (GitHub `Toastgeraet`).

- **Master copy:** `.claude/docs/roadmap.md` in the private app repo `Toastgeraet/reading-tracker`. This page
  is a user-facing extract of it. When the roadmap changes or a feature ships, update `index.html` in the same
  session, then update the "Last updated" date in the footer.
- **Audience:** the app's users (Tobi's friends, possibly international). English only. Features and phases
  in plain words. **No technical details**: no schema versions, OTA vs APK, libraries or internal names.
- **Feedback** comes from WhatsApp polls in the friends' group, not from the page. Don't add forms or votes.
- **Phase order isn't final** until Tobi decides it. Keep "Planned" for undecided phases.
- One self-contained `index.html`, no build step, no external scripts or fonts. Colors match the app's theme
  (`src/theme.ts` in the app repo), with dark mode via `prefers-color-scheme`. Check it at a 390 px phone
  width in light and dark mode before pushing.
- `.nojekyll` turns off GitHub's Jekyll processing. Keep it.
- Pushing to `main` publishes. GitHub Pages updates within a minute or two.
