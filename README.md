# Hyper Lint

[![style: very good analysis][very_good_analysis_badge]][very_good_analysis_link]
[![Powered by Mason](https://img.shields.io/endpoint?url=https%3A%2F%2Ftinyurl.com%2Fmason-badge)](https://github.com/felangel/mason)
[![License: MIT][license_badge]][license_link]

Hyperlint is a powerful linting package for Flutter and Dart projects. It provides a comprehensive set of rules that can help you identify and fix potential errors, style issues, and performance problems.

Hyperlint is built on top of the Dart linter, but it adds a number of additional features and rules that are specifically designed for Flutter and Dart projects. For example, Hyperlint includes rules to detect common Flutter widget errors, such as using the wrong widget type or setting the wrong properties. It also includes rules to enforce the Flutter style guide, such as using the correct naming conventions and indentation.

Hyperlint is also highly customizable. You can enable or disable individual rules, or even create your own custom rules. This makes it easy to tailor Hyperlint to meet the specific needs of your project and team.



## Installation 💻

**❗ In order to start using Hyper Lint you must have the [Dart SDK][dart_install_link] installed on your machine.**

Install via `dart pub add`:

```sh
dart pub add hyper_lint
```

---

## Installing

1. Add dependencies to `pubspec.yaml`

   Get the latest version in the 'Installing' tab
   on [pub.dev](https://pub.dev/packages/simple_ripple_animation/install)

    ```yaml
    dependencies:
        hyper_lint: <latest-version>
    ```

2. Run pub get.

   ```shell
   flutter pub get
   ```

3. Import package in the analysis_options.yaml

    ```yaml
    include: package:hyper_lint/analysis_options.yaml
    ```

## Suppressing Lints

There might some case where we have to suppres the linting error


### File Level

To surpress a specific lint rule of a specific file, use an `ignore_for_file` comment at the top of the file:

```dart
// ignore_for_file: public_member_api_docs

class Car {}

class Suv {}
```

### Project Level

To surpress a specific lint rule for an entire project, modify `analysis_options.yaml`:

```yaml
include: package:hyper_lint/analysis_options.yaml
linter:
  rules:
    public_member_api_docs: false
```

## Main Contributors
<table>
  <tr>
       <td align="center"><a href="https://github.com/jemisgoti"><img src="https://avatars.githubusercontent.com/u/46031164" width="100px;" alt=""/><br /><sub><b>Jemis Goti</b></sub></a></td>
 
</tr>
</table>
<br/>



## Feedback

If you have any feedback, please reach out to us at jemis.dev@gmail.com


## Thanks

Thank you for using this package and keep supporting opensource community.
 
[dart_install_link]: https://dart.dev/get-dart
[github_actions_link]: https://docs.github.com/en/actions/learn-github-actions
[license_badge]: https://img.shields.io/badge/license-MIT-blue.svg
[license_link]: https://opensource.org/licenses/MIT
[logo_black]: https://raw.githubusercontent.com/VGVentures/very_good_brand/main/styles/README/vgv_logo_black.png#gh-light-mode-only
[logo_white]: https://raw.githubusercontent.com/VGVentures/very_good_brand/main/styles/README/vgv_logo_white.png#gh-dark-mode-only
[mason_link]: https://github.com/felangel/mason
[very_good_analysis_badge]: https://img.shields.io/badge/style-very_good_analysis-B22C89.svg
[very_good_analysis_link]: https://pub.dev/packages/very_good_analysis
[very_good_coverage_link]: https://github.com/marketplace/actions/very-good-coverage
[very_good_ventures_link]: https://verygood.ventures
[very_good_ventures_link_light]: https://verygood.ventures#gh-light-mode-only
[very_good_ventures_link_dark]: https://verygood.ventures#gh-dark-mode-only
[very_good_workflows_link]: https://github.com/VeryGoodOpenSource/very_good_workflows
