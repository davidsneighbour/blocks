# DNB Blocks Bootstrap 5

This is a Hugo theme component with helpers to create and add favicons to your website.

## Installing

Enable modules in your own repository and add this module to your required modules in config.toml:

```shell script
hugo mod init github.com/username/reponame
```

Then add the module to your configuration:

```toml
[module]
[[module.imports]]
path = "github.com/dnb-hugo/blocks/bootstrap5"
```

The next time you run hugo it will download the latest version of the module.

## Updating

To update this module:

```shell
hugo mod get -u github.com/dnb-hugo/components/robots
```

To update all modules:

```shell
hugo mod get -u
```
