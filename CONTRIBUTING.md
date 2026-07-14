# Contributing to Battle of Penguin 3D

First off, thanks for taking the time to contribute! 🐧

## How to Contribute

1. **Fork** the repository and clone it locally.
2. **Create a branch** for your change:
   ```bash
   git checkout -b feat/your-feature-name
   ```
3. **Make your changes.** Since this is a single-file game, most edits will
   happen directly in `index.html` (and mirrored in `code/penguin-battle-3d.html`
   if you keep that copy in sync).
4. **Test locally** by opening `index.html` in a browser and playing through
   your change.
5. **Commit** using a clear, descriptive message:
   ```bash
   git commit -m "feat: add double-jump ability"
   ```
6. **Push** your branch and **open a Pull Request** against `main`.

## Guidelines

- Keep the game dependency-free (plain HTML/CSS/JS) unless there's a strong
  reason to add a library — discuss in an issue first.
- Match the existing code style (see the CSS custom properties at the top of
  `index.html` for the color/theme system).
- Keep PRs focused — one feature or fix per PR is easier to review.
- Update `docs/GAME-GUIDE.md` if your change affects gameplay or controls.

## Reporting Bugs / Requesting Features

Please use the issue templates:
- 🐛 [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md)
- 💡 [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md)

## Code of Conduct

This project follows a [Code of Conduct](CODE_OF_CONDUCT.md). By
participating, you agree to uphold it.

Thanks again for helping make Battle of Penguin 3D better! ❄️
