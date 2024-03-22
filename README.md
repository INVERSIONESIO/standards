
# Standards


## Contribution Guidelines

### Pull Requests

Try to do one pull request per change.

### Commit Message Format

We try our best to all our projects are adhered to [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).
This specification proposes an standard format to create commit message adding human and machine readable meaning.

#### Example

```text
<type>(<scope>): <short summary>
  │       │             │
  │       │             └─ Not capitalized. No period at the end.
  │       │
  │       └─ Commit Scope
  │
  └─ Commit Type: feat|fix|build|ci|docs|perf|refactor|test|chore
```

| Type     | Meaning                  | Description                                                                                                                             |
| -------- | ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------|
| feat     | Feature(s)               | A new feature                                                                                                                           |
| fix      | Bug Fixes                | A bug fix                                                                                                                               |
| docs     | Documentation            | Documentation only changes                                                                                                              |
| style    | Styles                   | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)                                  |
| refactor | Code Refactoring         | A code change that neither fixes a bug nor adds a feature                                                                               |
| perf     | Performance Improvements | A code change that improves performance                                                                                                 |
| test     | Tests                    | Adding missing tests or correcting existing tests                                                                                       |
| deps     | Dependencies             | Changes that only affect the project dependencies                                                                                       |
| ci       | Continuous Integrations  | Changes to our CI configuration files and scripts (example scopes: Github Actions)                                                      |
| chore    | Chores                   | Changes that don't modify src or test files, or make changes in src but are not really relevant for the project(e.g. remove comments)   |
| revert   | Reverts                  | Reverts a previous commit                                                                                                               |
