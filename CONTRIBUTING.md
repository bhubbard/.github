# Contributing Guidelines

Thank you for your interest in contributing! We welcome contributions ranging from bug reports and documentation fixes to performance optimizations and new features.

---

## Code of Conduct

All contributors and maintainers are expected to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Please treat all community members with respect and kindness.

---

## Development & Pull Request Guidelines

1. **Focused Changes:**
   Keep pull requests focused on a single change or bug fix. Avoid combining unrelated refactors or formatting changes with functional code.

2. **Code Standards:**
   - Adhere to the language-specific idioms of the repository (e.g. `cargo fmt` and `cargo clippy` in Rust projects, ESLint/Prettier in TypeScript/JavaScript, Ruff/Black in Python).
   - Ensure the repository's test suite passes cleanly before submitting a pull request.

3. **Conventional Commits:**
   Please format commit messages following [Conventional Commits](https://www.conventionalcommits.org/):
   - `feat(...)`: New feature or capability
   - `fix(...)`: Bug fix or security remediation
   - `perf(...)`: Performance optimization
   - `refactor(...)`: Code improvement without behavioral change
   - `test(...)`: Adding or updating test cases
   - `docs(...)`: Documentation updates

4. **Pull Request Process:**
   - Fill out the pull request template completely.
   - Link related issues (e.g. `Closes #123`).
   - Enable "Allow edits by maintainers" so maintainers can assist with minor fixes or rebasing.

---

## Reporting Issues

- **Bugs & Feature Requests:** Use the issue templates on the specific repository.
- **Security Vulnerabilities:** Follow the private reporting instructions in [SECURITY.md](SECURITY.md). Do **not** open public issues for security vulnerabilities.
