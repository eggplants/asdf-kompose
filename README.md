<div align="center">

# asdf-kompose ![Build](https://github.com/technikhil314/asdf-kompose/workflows/Build/badge.svg) ![Lint](https://github.com/technikhil314/asdf-kompose/workflows/Lint/badge.svg)

[kompose](https://github.com/technikhil314/kompose) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add kompose
# or
asdf plugin add https://github.com/technikhil314/asdf-kompose.git
```

kompose:

```shell
# Show all installable versions
asdf list-all kompose

# Install specific version
asdf install kompose latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kompose latest

# Now kompose commands are available
kompose --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/technikhil314/asdf-kompose/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nikhil Mehta](https://github.com/technikhil314/)
