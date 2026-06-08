# Contributing to CognitiveX

Thanks for your interest in contributing. This guide applies across the
CognitiveX organization.

## Ground rules

- Be respectful — see our [Code of Conduct](CODE_OF_CONDUCT.md).
- Open an issue before a large change so we can align on direction.
- One logical change per pull request. Smaller PRs get reviewed faster.

## Our design principle

> **LLMs are infrastructure, not IP.** The intelligence lives in the algorithms,
> memory architecture, and routing — not in the model. Every cognitive module
> defines its input and output schema first; the LLM renders language *last*.

If a change makes the system depend on a specific model's behavior to function
(not just to read better), it probably needs more structure first. Encode the
structure, then use the model to fill in the language.

## Workflow

1. Fork the repo and create a branch off the default branch.
2. Make your change with tests.
3. Run the project's linters and test suite locally (see each repo's README).
4. Open a pull request using the template, and link the issue it closes.

## Commit & PR style

- Use clear, imperative commit subjects (`fix(recall): handle empty query`).
- Conventional-commit prefixes (`feat`, `fix`, `docs`, `chore`, `refactor`,
  `test`) are appreciated.
- Describe **what** changed and **why** in the PR body, not just how.

## Reporting bugs and requesting features

Use the issue templates — they make sure we get the context we need to help.

## Security

Never report a security issue in a public issue or PR. Follow the process in
[SECURITY.md](SECURITY.md).
