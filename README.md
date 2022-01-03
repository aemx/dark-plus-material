# Dark+ Material Legacy

*This theme is forked from **Dark+ Material Version v2.4.4**. You can find the current version [**here**](https://github.com/vangware/dark-plus-material).*

![Dark+ Material Legacy logo](https://i.imgur.com/4yXZO0E.png)

## Reason behind this

I really love the default Dark+ Theme that comes with Visual Studio Code, but also love the Material Design Palette. The thing is I didn't found a good material theme (the coloring is always ugly for my taste). So I made this theme that implements the Material Design Palette in the Dark+ theme that comes with Visual Studio Code.

## How is this theme updated?

When VSCode makes an update, I run a script that takes the code from the VSCode repository, pipes it trough a mapping function and it results in the json file for this theme:

```plain
VSCode update -> mapping (1 VSCode color => 1 Material color) -> Dark+ Material update.
```

## Installing

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

```bash
ext install dark-plus-material-legacy
```