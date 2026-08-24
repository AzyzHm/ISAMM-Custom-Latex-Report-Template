# Contributing

Thanks for taking the time to contribute. This project is a LaTeX template,
so most contributions fall into one of a few categories: fixing a build
issue, improving the document structure, or making the template easier to
adapt. Small, focused changes are the easiest to review and merge.

Before contributing, please read our [Code of Conduct](CODE_OF_CONDUCT.md).
By participating, you agree to uphold it.

## Ways to contribute

- **Report a bug**: compilation errors, broken references, missing files,
  or anything that keeps the template from building cleanly.
- **Suggest an improvement**: a clearer file structure, a more flexible
  title page, better defaults, or documentation fixes.
- **Submit a fix**: pull requests are welcome for anything above, as well
  as typo fixes and formatting cleanups.

## Reporting a bug

Open an issue and include:

- What you expected to happen and what happened instead
- The exact error message or log output, if there is one
- Your LaTeX distribution and how you compiled (e.g. `pdflatex`,
  `latexmk`, Overleaf)
- Steps to reproduce, ideally a minimal example

## Suggesting an enhancement

Open an issue describing the change and why it would help. For anything
that changes the overall structure (renaming files, changing the include
order, altering the default styling), it helps to explain the use case
first so the change can be discussed before any work is done.

## Making changes

1. Fork the repository and create a branch from `main`.
2. Make your changes, keeping them focused on a single issue or feature.
3. Compile the document locally (or on Overleaf) to confirm it still
   builds without errors or new warnings.
4. Commit your changes with a clear, descriptive message.
5. Open a pull request against `main` and describe what you changed and
   why.

## Style guidelines

- Keep the template generic. Avoid hardcoding institution-specific text,
  names, or content outside of clearly marked placeholder sections.
- Match the existing formatting conventions (indentation, comments,
  naming) rather than introducing a new style in the same file.
- Prefer small, reviewable commits over one large change.
- Update the README if your change affects how the template is used or
  compiled.

## Questions

If anything is unclear, feel free to open an issue and ask before
submitting a pull request.