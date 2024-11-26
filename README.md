<div align="center">

# asdf-tfenv [![Build](https://github.com/pewty-fr/asdf-tfenv/actions/workflows/build.yml/badge.svg)](https://github.com/pewty-fr/asdf-tfenv/actions/workflows/build.yml) [![Lint](https://github.com/pewty-fr/asdf-tfenv/actions/workflows/lint.yml/badge.svg)](https://github.com/pewty-fr/asdf-tfenv/actions/workflows/lint.yml)

[tfenv](https://github.com/tfutils/tfenv) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-tfenv  ](#asdf-tfenv--)
- [Contents](#contents)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add tfenv
# or
asdf plugin add tfenv https://github.com/pewty-fr/asdf-tfenv.git
```

tfenv:

```shell
# Show all installable versions
asdf list-all tfenv

# Install specific version
asdf install tfenv latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tfenv latest

# Now tfenv commands are available
tfenv --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pewty-fr/asdf-tfenv/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tanguy Falconnet](https://github.com/pewty-fr/)
