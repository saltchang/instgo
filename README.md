# Instgo

A simple [Go Language](https://golang.org) installer for Linux & macOS.

![instgo](https://github.com/saltchang/instgo/blob/main/assets/demo.jpg?raw=true)

## Usage

```bash
bash <(curl -sS https://raw.githubusercontent.com/saltchang/instgo/main/instgo)
```

This installation script will prompt you to select a version of Go to install,  
and download the package from official source, extract and install the packages for you.

Note that this script use the default path(`/usr/local/go`) to install the packages.  
It may prompt you the password for root permission to remove the previous installation and install the new one.

After packages installed, the script will add the path to Go into your shell profile(`$HOME/.zshrc`, `$HOME/.bashrc`, or `$HOME/.bash_profile`) automatically.

For more information, please see the [official document of Go](https://golang.org/doc/install).

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/saltchang/instgo/blob/main/LICENSE)
