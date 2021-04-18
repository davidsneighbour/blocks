## DNB Blocks Bootstrap

This is a Hugo theme component with blocks to create a website based on Bootstrap 5.

### Installation

Enable modules in your own repository and add this module to your required modules in config.toml:

```shell script
hugo mod init github.com/username/reponame
```

Then add the module to your configuration:

```toml
[module]
[[module.imports]]
path = "github.com/dnb-hugo/blocks/bootstrap"
```

The next time you run hugo it will download the latest version of the module.

### Update

To update this module:

```shell
hugo mod get -u github.com/dnb-hugo/blocks/bootstrap
```

To update all modules:

```shell
hugo mod get -u
```
