# Code Quality

[![Circle CI Status](https://circleci.com/gh/bkuhlmann/code_quality.svg?style=svg)](https://circleci.com/gh/bkuhlmann/code_quality)

These are global configurations for ensuring high quality *and* consistent software development
practices. Feel free to link to this project in order to apply these configurations to your
projects. You may also fork this project to customize further for your specific needs.

*NOTE: This project only supports tools which can import configurations via a URL.*

<!-- Tocer[start]: Auto-generated, don't remove. -->

## Table of Contents

  - [Features](#features)
  - [Requirements](#requirements)
  - [Setup](#setup)
  - [Usage](#usage)
  - [Versioning](#versioning)
  - [Code of Conduct](#code-of-conduct)
  - [Contributions](#contributions)
  - [License](#license)
  - [History](#history)
  - [Credits](#credits)

<!-- Tocer[finish]: Auto-generated, don't remove. -->

## Features

- Provides global configurations for tools that support URL imports.
- Provides global configurations for the following tools:
  - [Rubocop](https://github.com/bbatsov/rubocop)

## Requirements

- Familiarity with [Rubocop](https://github.com/bbatsov/rubocop).
- Rubocop 0.49.0 or higher.

## Setup

No setup is required other than what is mentioned in the *Requirements* section. If you would like
to use the project, locally, you can do so by opening a terminal window and executing the following
commands:

    git clone https://github.com/bkuhlmann/code_quality.git
    cd code_quality

Edit any of the `configurations/*` files as you see fit.

## Usage

This project is designed to be linked to your own projects. This can be done via one of the
following options:

Current Version (stable)

    https://raw.githubusercontent.com/bkuhlmann/code_quality/v1.2.0/configurations/<pick a file>

Master Version (unstable)

    https://raw.githubusercontent.com/bkuhlmann/code_quality/master/configurations/<pick a file>

Here is a more concrete example using Rubocop. In your local `.rubocop.yml`, replace the contents
with the following:

    inherit_from:
      - https://raw.githubusercontent.com/bkuhlmann/code_quality/v1.2.0/configurations/rubocop/ruby.yml
      - https://raw.githubusercontent.com/bkuhlmann/code_quality/v1.2.0/configurations/rubocop/rails.yml

Now you are configured to import from a global configuration. For further details, check out the
[Rubocop Documentation](https://rubocop.readthedocs.io/en/latest/configuration /#inheriting-
configuration-from-a-remote-url).

## Versioning

Read [Semantic Versioning](http://semver.org) for details. Briefly, it means:

- Major (X.y.z) - Incremented for any backwards incompatible public API changes.
- Minor (x.Y.z) - Incremented for new, backwards compatible, public API enhancements/fixes.
- Patch (x.y.Z) - Incremented for small, backwards compatible, bug fixes.

## Code of Conduct

Please note that this project is released with a [CODE OF CONDUCT](CODE_OF_CONDUCT.md). By
participating in this project you agree to abide by its terms.

## Contributions

Read [CONTRIBUTING](CONTRIBUTING.md) for details.

## License

Copyright (c) 2017 [Alchemists](https://www.alchemists.io).
Read [LICENSE](LICENSE.md) for details.

## History

Read [CHANGES](CHANGES.md) for details.
Built with [Gemsmith](https://github.com/bkuhlmann/gemsmith).

## Credits

Developed by [Brooke Kuhlmann](https://www.alchemists.io) at
[Alchemists](https://www.alchemists.io).
