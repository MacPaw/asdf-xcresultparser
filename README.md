<div align="center">

# asdf-xcresultparser [![Build](https://github.com/MacPaw/asdf-xcresultparser/actions/workflows/build.yml/badge.svg)](https://github.com/MacPaw/asdf-xcresultparser/actions/workflows/build.yml) [![Lint](https://github.com/MacPaw/asdf-xcresultparser/actions/workflows/lint.yml/badge.svg)](https://github.com/MacPaw/asdf-xcresultparser/actions/workflows/lint.yml)

[xcresultparser](https://github.com/a7ex/xcresultparser) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add xcresultparser
# or
asdf plugin add xcresultparser https://github.com/MacPaw/asdf-xcresultparser.git
```

xcresultparser:

```shell
# Show all installable versions
asdf list-all xcresultparser

# Install specific version
asdf install xcresultparser latest

# Set a version globally (on your ~/.tool-versions file)
asdf global xcresultparser latest

# Now xcresultparser commands are available
xcresultparser --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MacPaw/asdf-xcresultparser/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [MacPaw](https://github.com/MacPaw/)
