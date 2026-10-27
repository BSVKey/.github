# Security Policy

This policy covers every repository in the BSVKey organization that does not have its
own `SECURITY.md`.

## Reporting a vulnerability

Please report security issues privately to **embryospace@gmail.com**. Do not open a
public issue for a vulnerability.

Include:
- the repository and the commit or package version affected
- what an attacker could do, and under what conditions
- steps or code to reproduce it, if you have them

We will acknowledge your report, work with you on a fix, and agree on a disclosure date
before anything is made public. You can also use GitHub's private vulnerability
reporting where a repository has it turned on.

## What matters most

Please tell us first about anything that could:
- move, lock or lose someone's funds, or let a payment be replayed or double-counted
- let a receipt, signature or custody record verify when it should not
- expose a private key, wallet seed or channel secret
- let one user act as another (for example in `.key` sign-in)

## Scope

- Most repositories here are reference implementations, not audited production
  libraries. Review them, and run your own assessment, before relying on them.
- You hold your own keys. None of this code needs us to custody your keys or funds.
- Hosted services (bsvkey.com and its subdomains) are in scope too. Please do not run
  tests that spend other people's funds, degrade service for others, or access data that
  is not yours.
