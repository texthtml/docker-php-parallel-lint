# PHPCS

This a docker image for [php-parallel-lint](https://github.com/JakubOnderka/PHP-Parallel-Lint)

## Usage

Checking php file syntax:

```
docker run -v /path/to/php/files/:/scripts/ texthtml/php-parallel-lint parallel-lint /scripts/
```
