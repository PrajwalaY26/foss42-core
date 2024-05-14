# foss42

Core Python library for foss42 Open Source APIs. This library provides a set of utility functions for data conversion, validation, generation, transformation, machine learning, business intelligence, visualization, charts, language graphs, data mapping, and more.

!Discord Server Invite](https://discord.gg/2s49SCNfyJ)

![PyPI](https://img.shields.io/pypi/v/foss42?logo=python&logoColor=yellow&style=for-the-badge)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/foss42?logo=python&logoColor=yellow&style=for-the-badge)

Core Python library for [foss42 Open Source APIs](https://github.com/foss42/api). 

This project is participating in GSSoC 2024.

![gssoc-logo-1](https://github.com/foss42/awesome-generative-ai-apis/assets/1382619/670b651a-15d7-4869-a4d1-6613df09fa37)

## Table of Contents
- Installation
- Available Functions
- Usage Example
- Contributing
- License

## Installation
```bash
pip3 install foss42
```

## Available Functions

See the full list of available functions [here](https://foss42.github.io/foss42-core).

## Usage Example

```python
>>> import foss42.text.humanize as hz
>>> hz.humanize_bytes(1126,
                      2,
                      prefix = True,
                      trailing_zeros = True)
>>> '1.10 kilobytes'
```

## Contributing

Contributors should go through the [Contributing Guide](https://github.com/foss42/foss42-core/blob/main/CONTRIBUTING.md) to learn how to setup development environment, raise an issue and send across a PR.

## License
This project is licensed under the Apache License. See the LICENSE file for details.

