<div align="center">

# asdf-flipper [![Build](https://github.com/jeffryang24/asdf-flipper/actions/workflows/build.yml/badge.svg)](https://github.com/jeffryang24/asdf-flipper/actions/workflows/build.yml) [![Lint](https://github.com/jeffryang24/asdf-flipper/actions/workflows/lint.yml/badge.svg)](https://github.com/jeffryang24/asdf-flipper/actions/workflows/lint.yml)


[flipper](https://fbflipper.com/docs/getting-started/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add flipper
# or
asdf plugin add flipper https://github.com/jeffryang24/asdf-flipper.git
```

flipper:

```shell
# Show all installable versions
asdf list-all flipper

# Install specific version
asdf install flipper latest

# Set a version globally (on your ~/.tool-versions file)
asdf global flipper latest

# Now flipper commands are available
flipper --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jeffryang24/asdf-flipper/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jeffry Angtoni](https://github.com/jeffryang24/)
