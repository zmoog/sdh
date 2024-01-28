# sdh

[![PyPI](https://img.shields.io/pypi/v/sdh.svg)](https://pypi.org/project/sdh/)
[![Changelog](https://img.shields.io/github/v/release/zmoog/sdh?include_prereleases&label=changelog)](https://github.com/zmoog/sdh/releases)
[![Tests](https://github.com/zmoog/sdh/actions/workflows/test.yml/badge.svg)](https://github.com/zmoog/sdh/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/zmoog/sdh/blob/master/LICENSE)

CLI tool to help with SDHs (internal support developer help requests)

## Installation

Install this tool using `pip`:

    pip install sdh

## Usage

For help, run:

    sdh --help

You can also use:

    python -m sdh --help

## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:

    cd sdh
    python -m venv venv
    source venv/bin/activate

Now install the dependencies and test dependencies:

    pip install -e '.[test]'

To run the tests:

    pytest
