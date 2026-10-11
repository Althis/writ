# Writ

Intent-traced verification for AI-assisted codebases. Writ runs in CI on
every commit, PR or release and reports which intentions are verified,
which rest on assumptions, and which are untested. Passing it is the
permission to proceed.

Writ reads the **canon**, the intent format shared with
[HeadCanon](https://github.com/althis/headcanon), and drives the test
tools a team already uses instead of replacing them.

## Status

Not started. Writ begins once HeadCanon is in use on a real project. The
design brief is in [docs/design-brief-v0.md](docs/design-brief-v0.md).

## License

Apache 2.0. See [LICENSE](LICENSE) and [NOTICE](NOTICE).
