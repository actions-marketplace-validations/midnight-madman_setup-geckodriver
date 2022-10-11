![build-test](https://github.com/midnight-madman/setup-geckodriver/workflows/build-test/badge.svg)

# setup-geckodriver

This action sets by Geckodriver for use in actions by:

- downloading and caching a version of Geckodriver by version and add to PATH

## Usage

See [action.yml](action.yml)

Basic usage:

```yaml
steps:
  - uses: midnight-madman/setup-geckodriver@latest
  - run: geckodriver --version
```

## License

[MIT](LICENSE)
