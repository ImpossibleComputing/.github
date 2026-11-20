# Contributing

These defaults apply to every repository in the ImpossibleComputing organization that does not have its own `CONTRIBUTING.md`.

## Before you start

- **Bugs:** search the existing issues first. If it isn't there, open one with the bug template.
- **Features:** open an issue with the feature template before writing code. A pull request with no agreed issue may be closed.
- **Security issues:** don't file them as issues. See [SECURITY.md](SECURITY.md).

## Pull requests

- Keep each one to a single change. Split refactors from behaviour changes.
- Say what changed and why in the description. Link the issue.
- Add or update tests for the change. Run the repository's test and lint commands before you push.
- Write commit messages in the imperative: "Add retry to capture client", not "Added retries".

## Writing style

Write docs, UI copy and error messages plainly, literally and exactly.

- Say what it is. Write "The browser refused the clipboard", not "Oops!".
- Never hide limits. A missing feature still shows, and says why.
- Numbers are evidence. Give real units: `9.8 s`, `14,880 tokens`.
- No emoji, no exclamation marks, no hype words.
