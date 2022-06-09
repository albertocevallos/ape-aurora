# Ape Aurora Ecosystem Plugin

Ecosystem Plugin for Aurora support in Ape

## Dependencies

- [python3](https://www.python.org/downloads) version 3.7 or greater, python3-dev

## Installation

### via `ape`

You can install this plugin using `ape`:

```bash
ape plugins install aurora
```

or via config file:

```yaml
# ape-config.yaml
plugins:
  - name: aurora
```

### via `pip`

You can install the latest release via [`pip`](https://pypi.org/project/pip/):

```bash
pip install ape-aurora
```

### via `setuptools`

You can clone the repository and use [`setuptools`](https://github.com/pypa/setuptools) for the most up-to-date version:

```bash
git clone https://github.com/albertocevallos/ape-aurora.git
cd ape-aurora
python3 setup.py install
```

## Quick Usage

Installing this plugin adds support for the Aurora ecosystem:

```bash
ape console --network aurora:mainnet
```

## Development

Comments, questions, criticisms and pull requests are welcomed.

## License

This project is licensed under the [Apache 2.0](LICENSE).
