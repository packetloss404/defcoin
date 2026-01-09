# Contributing to Defcoin Core

The Defcoin Core project welcomes contributions from anyone in the form of
peer review, testing, and patches.

## Getting Started

New contributors are welcome and needed.

Reviewing and testing is highly valued and the most effective way you can
contribute as a new contributor. It also will teach you much more about the
code and process than opening pull requests.

Before you start contributing, familiarize yourself with the Defcoin Core
build system and tests. Refer to the documentation in the repository on how
to build Defcoin Core and how to run the unit and functional tests.

## Repository

- **Main Repository**: https://github.com/packetloss404/defcoinv2
- **Issues**: https://github.com/packetloss404/defcoinv2/issues
- **Original Defcoin**: https://github.com/mspicer/defcoin

## Contributing Process

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Make your changes
4. Run tests to ensure nothing is broken
5. Commit your changes with a clear message
6. Push to your fork
7. Open a Pull Request

## Code Style

Defcoin Core is based on Litecoin/Bitcoin Core. Please follow the existing
code style in the repository:

- Use 4 spaces for indentation (no tabs)
- Follow the naming conventions used in existing code
- Add comments for complex logic
- Write clear commit messages

## Testing

Before submitting a pull request:

```bash
# Run unit tests
make check

# Run functional tests
test/functional/test_runner.py
```

## Communication

- Open an issue for bug reports or feature requests
- Use pull request comments for code-related discussions

## License

By contributing to Defcoin Core, you agree that your contributions will be
licensed under the MIT License.
