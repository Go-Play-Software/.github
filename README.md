# .github

This repository contains organization-wide GitHub configuration for **Go Play! Software**, including:

- **`profile/README.md`** — The organization profile shown on the [Go Play! Software GitHub page](https://github.com/Go-Play-Software)

It can also hold default community health files (e.g., `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`) that apply to all repositories in the organization when not overridden at the repo level.

## Structure

```
.
├── CONTRIBUTING.md      # Default contribution guidance
├── profile/
│   └── README.md        # Organization profile page
└── README.md            # This file
```

## About

The `.github` repository is a special GitHub repository used to share default files and settings across an entire organization. Files placed here serve as fallbacks for repositories that do not define their own versions.

## Contribution defaults

[CONTRIBUTING.md](CONTRIBUTING.md) supplies the organization fallback for reusable
code, supported modern APIs and concise comments. Repository-specific guides and
contribution rules take precedence. Keep the public profile in `profile/README.md`
focused on the company rather than internal engineering instructions.
