# chatgpt-export-to-sqlite

[![PyPI](https://img.shields.io/pypi/v/chatgpt-export-to-sqlite.svg)](https://pypi.org/project/chatgpt-export-to-sqlite/)
[![Changelog](https://img.shields.io/github/v/release/RamVasuthevan/chatgpt-export-to-sqlite?include_prereleases&label=changelog)](https://github.com/RamVasuthevan/chatgpt-export-to-sqlite/releases)
[![Tests](https://github.com/RamVasuthevan/chatgpt-export-to-sqlite/actions/workflows/test.yml/badge.svg)](https://github.com/RamVasuthevan/chatgpt-export-to-sqlite/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/RamVasuthevan/chatgpt-export-to-sqlite/blob/master/LICENSE)

Convert ChatGPT to SQLite

## Installation

Install this tool using `pip`:
```bash
pip install chatgpt-export-to-sqlite
```
## Usage

For help, run:
```bash
chatgpt-export-to-sqlite --help
```
You can also use:
```bash
python -m chatgpt_export_to_sqlite --help
```
## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:
```bash
cd chatgpt-export-to-sqlite
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
python -m pytest
```
