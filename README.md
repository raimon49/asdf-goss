# asdf-goss

[![plugin test](https://github.com/raimon49/asdf-goss/workflows/plugin%20test/badge.svg)](https://github.com/raimon49/asdf-goss/actions/workflows/asdf.yml)
[![Build Status](https://travis-ci.org/raimon49/asdf-goss.svg?branch=master)](https://travis-ci.org/raimon49/asdf-goss)

[Goss](https://goss.rocks) as a server testing tool plugin for [asdf version manager](https://asdf-vm.com/)

## Installation

```bash
$ asdf plugin add goss https://github.com/raimon49/asdf-goss.git
```

## Usage

```bash
# Install any version of Goss
$ asdf install goss v0.3.6

# Set the version of Goss you want
$ asdf global goss v0.3.6
$ goss --version
goss version v0.3.6
```

## License

[MIT License](LICENSE)
