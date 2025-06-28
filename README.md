<div align="center">

# asdf-sqlcmd [![Build](https://github.com/ahyalfan/asdf-sqlcmd/actions/workflows/build.yml/badge.svg)](https://github.com/ahyalfan/asdf-sqlcmd/actions/workflows/build.yml) [![Lint](https://github.com/ahyalfan/asdf-sqlcmd/actions/workflows/lint.yml/badge.svg)](https://github.com/ahyalfan/asdf-sqlcmd/actions/workflows/lint.yml)

[sqlcmd](docs) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add sqlcmd
# or
asdf plugin add sqlcmd https://github.com/ahyalfan/asdf-sqlcmd.git
```

sqlcmd:

```shell
# Show all installable versions
asdf list-all sqlcmd

# Install specific version
asdf install sqlcmd latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sqlcmd latest

# Now sqlcmd commands are available
sqlcmd --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ahyalfan/asdf-sqlcmd/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ahmad alfandi](https://github.com/ahyalfan/)
