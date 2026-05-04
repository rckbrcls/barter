# Contributing to Barter

Barter is an early Flutter project. The current implementation is still close to the default Flutter counter app, while the product direction is documented in `REQUIREMENTS.md`.

Contributions should make the repository more accurate, testable, and aligned with the Barter product direction without claiming unfinished marketplace behavior as complete.

## Development Setup

Install Flutter for the platform you want to target, then restore dependencies:

```sh
flutter pub get
```

Run the app on a Flutter-supported device:

```sh
flutter devices
flutter run -d <device-id>
```

Run checks before submitting changes:

```sh
flutter analyze
flutter test
```

## Contribution Guidelines

- Keep app strings, code, comments, and documentation in English.
- Keep product claims honest. If a feature is only planned in `REQUIREMENTS.md`, do not present it as implemented in `README.md`.
- Update `test/widget_test.dart` when replacing the starter counter UI.
- Keep Flutter-generated platform files unchanged unless the change is intentional and documented.
- Replace starter metadata such as `A new Flutter project.`, `Flutter Demo`, and `com.example.barter` only when the corresponding app metadata work is in scope.
- Add new documentation only when the codebase has enough real behavior to justify it.
- Do not add secrets, credentials, API keys, signing files, or local machine paths to the repository.

## Pull Request Checklist

Before opening a pull request, verify:

- The change is based on current code, not only on the product concept.
- `flutter analyze` passes.
- `flutter test` passes.
- Documentation was updated if user-visible behavior, project setup, or architecture changed.
- New product behavior has tests or a clear note explaining why tests were not added.
- No generated build output or local tool artifacts were committed.

## Project Workflow Notes

No repository-specific branch naming rule, commit convention, release process, or CI workflow is defined in the current codebase.

TODO: not identified in the current codebase - contribution review owner and expected pull request review process.
