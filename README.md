# APEALED Analysis

[`lints-`](https://pub.dev/packages/lints) and [`very_good_analysis-`](https://pub.dev/packages/very_good_analysis) inspired lint rules but  with my own taste.

[![BSD 3-Clause "New" or "Revised" license](https://img.shields.io/badge/license-BSD-3)](./LICENSE)

## Usage

Add to project:

```sh
dart pub add dev:apealed_analysis
# or
flutter pub add dev:apealed_analysis
```

Include in your `analysis_options.yaml`:

```yaml
include: package:apealed_analysis/analysis_options.yaml
```

## Features

- Strict typing for dart language
- Excludes commonly generated files like `*.freezed.dart` and `*.g.dart`
- Excludes `__brick__` templates (from [`mason`](https://pub.dev/packages/mason_cli))
- Strong linter ruleset (comparable to [`very_good_analysis`](https://pub.dev/packages/very_good_analysis))