## Contributing

👍🎉 Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great. 🎉👍

The following is a set of guidelines for contributing to **TCM Frontend App**.
These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

### Pull Requests Process

Please follow these steps to have your contribution in TCM:

1. Follow all instructions in [the template](PULL_REQUEST_TEMPLATE.md)
2. Follow the [styleguides](#styleguides)
3. Assign the Jira Ticket(s) to yourself to avoid concurent work on the same task.
4. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A PR Reviewer will re-run the status check for you.</details>

## Styleguides

### Branch name

Develoment branches should follow the following format: `<type>/<name>`
To make it easier, type uses the same values as the type in commit messages and must be one of the following:

| Type        | Description                                                                                                 |
| ----------- | ----------------------------------------------------------------------------------------------------------- |
| `build`     | Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)         |
| `ci`        | Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs) |
| `docs`      | Documentation only changes                                                                                  |
| `feature`   | A new feature                                                                                               |
| `fix`       | A bug fix                                                                                                   |
| `perf`      | A code change that improves performance                                                                     |
| `refactor`  | A code change that neither fixes a bug nor adds a feature                                                   |
| `style`     | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)      |
| `test`      | Adding missing tests or correcting existing tests                                                           |
| `chore`     | Changes to the build process or auxiliary tools (example scopes: gulp, broccoli, npm)                       |
| `reasearch` | Researching and learning new technologies                                                                   |

#### Release branches

The following branches are used for releases.
Changes should be made to development branches and merge into release branches through pull requests.

| Branch | Tag    | Description                |
| ------ | ------ | -------------------------- |
| `main` | latest | Currently released version |

### Commit message

Commit messages are used for automatic versioning.
It is therefore following the [conventional commits](https://www.conventionalcommits.org/) guidelines.

_The commit message format will be checked in the project using pre-commit hooks._

The format is defined as follows:

```
<type>: <description>

[optional body]

[optional footer(s)]
```

#### Type

Type must be one of the following:
To make it easier, type uses the same values as the type in commit messages and must be one of the following:

| Type       | Description                                                                                                 |
| ---------- | ----------------------------------------------------------------------------------------------------------- |
| `build`    | Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)         |
| `ci`       | Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs) |
| `docs`     | Documentation only changes                                                                                  |
| `feat`     | A new feature                                                                                               |
| `fix`      | A bug fix                                                                                                   |
| `perf`     | A code change that improves performance                                                                     |
| `refactor` | A code change that neither fixes a bug nor adds a feature                                                   |
| `style`    | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)      |
| `test`     | Adding missing tests or correcting existing tests                                                           |
| `chore`    | Changes to the build process or auxiliary tools (example scopes: gulp, broccoli, npm)                       |

## Resources

- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [Writing good commits](https://github.blog/2022-06-30-write-better-commits-build-better-projects/)
- [GitHub Help](https://help.github.com)
