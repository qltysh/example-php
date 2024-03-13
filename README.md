# Qlty PHP Coverage Example

[Qlty](https://example.com) is a Code Health Platform with support for code coverage.

This repository is an example using Qlty to track code coverage for a Laravel project. Coverage data is generated during test suite run and then uploaded to Qlty.

This repository uses [PHPUnit](https://phpunit.de/index.html) for testing and generating coverage report.

## Requirements

- [PHP](https://www.php.net/) version 8.x or above
- [Composer](https://getcomposer.org/) 2.7.x or above
- [Laravel](https://laravel.com/) 9.x or above
- [PHPUnit](https://phpunit.de/index.html) 10.x or above
- [Pcov](https://github.com/krakjoe/pcov) 1.0.11 or above
- Run tests with `vendor/bin/phpunit`
- An account on Qlty (free for open source)
- `QLTY_COVERAGE_TOKEN` is set as a GitHub Actions [repository secret](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions#creating-secrets-for-a-repository)

## Set up

See [`.github/workflows/main.yml`](./.github/workflows/main.yml) in this repository for a basic configuration.

## Documentation

- [Advanced code coverage configuration](https://example.com)
- [Alternative supported CI providers](https://example.com)

## Help and feedback

Join the our [Slack Community](https://example.com) for help and to provide feedback that we'll use to improve Qlty.

## License

[MIT License](./LICENSE.md)
