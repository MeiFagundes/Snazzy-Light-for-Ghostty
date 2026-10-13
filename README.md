# Snazzy Light for Ghostty

A bright Ghostty theme adapted from [Snazzy Light for VS Code](https://github.com/loilo/vscode-snazzy-light). It uses the original terminal ANSI colors in Ghostty’s native theme format.

## Install

From this repository’s directory, copy the theme into Ghostty’s custom themes folder:

```sh
theme_dir="${XDG_CONFIG_HOME:-$HOME/.config}/ghostty/themes"
mkdir -p "$theme_dir"
cp "Snazzy Light" "$theme_dir/Snazzy Light"
```

## Use

Set the theme in your Ghostty config and reload the configuration:

```ini
theme = Snazzy Light
```

For automatic switching with system appearance, pair it with Ghostty’s built-in Snazzy dark theme:

```ini
theme = light:Snazzy Light,dark:Snazzy
```

The theme sets only colors. Background opacity, blur, fonts, and platform options are configured separately. Existing color overrides in your Ghostty config take precedence over the theme.

See [Ghostty’s theme documentation](https://ghostty.org/docs/features/theme) for theme installation and configuration details.

## License

MIT. See [LICENSE](LICENSE) for the original copyright and permission notice from Florian Reuschel. The ANSI palette comes from Snazzy Light, cursor and selection colors are adapted for this port.
