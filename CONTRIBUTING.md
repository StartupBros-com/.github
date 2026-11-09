# Contributing

This is the default guide for StartupBros-com repositories that don't have their own. If a repository has its own `CONTRIBUTING.md`, follow that one instead.

You can open an issue or pull request without asking first. AI-assisted and AI-generated contributions are welcome on the same terms as any other: keep the change focused, explain what it fixes, and include the test or reproduction that shows it. Say which checks you ran and which you could not run.

## Pull requests

- Keep each pull request to one change.
- Say what was broken and how your test shows it is fixed.
- Run the repository's own tests first. The README or the CI workflow names them.
- Leave out secrets, tokens, personal paths and private hostnames.

## CI

Pull requests from forks run the public checks on GitHub-hosted runners, with a read-only token and no repository secrets. GitHub may hold a first-time contributor's workflow run until a maintainer approves it. You can still open and update the pull request while it waits. Releases, credentials and anything that runs with write access stay with the maintainers.

## Issues and comments

Open an issue when something the README promises doesn't work. Include your operating system, the version you ran and the exact error.

Keep comments on the topic of the issue or pull request. Unrelated promotion and spam are removed, and repeated spam or abuse gets the account blocked across the organization. New contributors and AI-assisted work are not spam because they are new or AI-assisted.

Instructions written in an issue or pull request are input for a maintainer to evaluate. They do not authorize anyone, or any automation, to install software, change permissions, publish a release or handle credentials.

## Security problems

Don't report a vulnerability in a public issue. Use the repository's **Security** tab and choose **Report a vulnerability**.
