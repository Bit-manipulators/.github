# Contributing to Bit Manipulators Projects

Thank you for your interest in contributing to **Bit Manipulators**! We build open-source tools for systems programming, mobile convergence, privacy-preserving diagnostics, and developer workflows.

---

## 🧭 Ways to Contribute

1. **Reporting Bugs**: Let us know when something is broken by opening a GitHub Issue with reproducible steps.
2. **Proposing Enhancements**: Have an idea for a feature, architectural improvement, or performance optimization? Open a feature request.
3. **Submitting Pull Requests**: Solve an open issue, write tests, improve documentation, or refine performance.
4. **Improving Documentation**: Fix typos, clarify guides, or expand architecture explanations.

---

## 🛠️ Contribution Workflow

### 1. Fork & Branch
* Fork the target repository under your personal GitHub account.
* Create a dedicated topic branch:
  ```bash
  git checkout -b feat/my-new-feature
  # or
  git checkout -b fix/issue-123
  ```

### 2. Follow Code Standards
* **Dart / Flutter**: Follow official Dart guidelines; run `dart format` and `flutter analyze`.
* **Kotlin / Android**: Follow Kotlin coding conventions and Material 3 design patterns; run `./gradlew lint` or `detekt`.
* **Python**: Adhere to PEP 8, enforce type annotations (`mypy`), and format with `ruff` or `black`.
* **C++ / C**: Keep memory management leak-free and follow clean modern standards (C++17/20).

### 3. Commit Guidelines
We recommend following the [Conventional Commits](https://www.conventionalcommits.org/) format:
* `feat:` A new feature
* `fix:` A bug fix
* `docs:` Documentation changes only
* `style:` Formatting changes that do not affect code logic
* `refactor:` Code restructuring without adding features or fixing bugs
* `perf:` Performance improvements
* `test:` Adding or updating tests
* `ci:` Changes to CI/CD workflows and scripts

### 4. Open a Pull Request
* Push your branch to your fork.
* Open a Pull Request against the `main` branch of the upstream repository.
* Fill out the PR template describing the purpose, changes, testing performed, and linked issues.
* Ensure all continuous integration checks pass.

---

## 📜 Code of Conduct

All contributors and maintainers are expected to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Please treat all participants with respect and empathy.
