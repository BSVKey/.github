# Contributing

Thanks for your interest in BSVKey. This guide applies to every repository in the
organization that does not have its own `CONTRIBUTING.md`.

## Before you start

- For a bug, open an issue with steps to reproduce it.
- For a new feature or a larger change, open an issue first so we can agree on the
  approach before you spend time on it.
- For a security issue, do not open an issue. See [SECURITY.md](SECURITY.md).

## Ground rules

- **No secrets.** Never commit private keys, WIFs, wallet seeds, channel secrets,
  `.env` files or funded credentials. Use your own environment for anything live.
- **Tests must pass.** Run `npm test` before you open a pull request, and add a test
  with any change in behaviour.
- **Keep dependencies light.** Many of these packages have zero runtime dependencies on
  purpose. Please discuss before adding one.
- **Name the chain.** Write "Bitcoin BSV" or "BSV" in docs and messages, not a bare
  "Bitcoin".

## Pull requests

1. Fork the repository and create a branch.
2. Make the change, run `npm test`, and update the README if behaviour changed.
3. Open a pull request that says what changed and why.

By submitting a contribution you agree it is licensed under the repository's license
(see its `LICENSE` file).

## Developer Certificate of Origin

Please sign off your commits (`git commit -s`) to certify you have the right to submit
the work under the project license (the [DCO](https://developercertificate.org/)).
