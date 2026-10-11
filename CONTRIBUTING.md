# Contributing to Go Play! Software

Start with the repository's own guide, build instructions and contribution rules.
They take precedence over these organization defaults.

- Search for an existing implementation before adding code. Give repeated
  operations with the same contract one focused implementation, and preserve
  differences in policy and state ownership. Avoid abstractions for hypothetical
  future consumers.
- Favor modern language and platform features that the project's supported
  toolchain and targets can use. Check behavior and availability; do not change
  dependencies or deployment requirements as an incidental cleanup.
- Use descriptive names and concise comments explaining intent or constraints.
  Keep required API documentation, attribution and useful invariant explanations.
  Link to one maintained document for extended background.
- Submit changes through a branch and pull request. Describe the behavior or
  guidance changed, report the checks actually run, and follow the repository's
  review and merge requirements.

Org members can find the detailed workflow in the private `goplay` marketplace
at `Go-Play-Software/claude-plugins`. These defaults remain usable without access
to that repository.
