# Supersonic Themes

A community theme collection for [Supersonic](https://github.com/dweymouth/supersonic), inspired by carefully crafted color systems such as Gruvbox.

![Supersonic Themes preview](assets/preview.png)

## Themes

Each palette is available with three accent colors: **Red**, **Blue**, and **Purple**.

| Family | Appearance | Accents |
| --- | --- | --- |
| Gruvbox Dark | Warm dark theme | Red, Blue, Purple |
| Gruvbox Material Dark | Softer dark theme | Red, Blue, Purple |
| Gruvbox Light | Warm light theme | Red, Blue, Purple |

### Download a theme

Choose a `.toml` file from [`themes/`](themes/), then place it in the Supersonic theme directory used by your installation.

In Supersonic, open **Settings → Appearance → Theme** and select the theme. If your version exposes a separate mode selector, choose the matching Dark or Light mode.

> Theme file compatibility can vary between Supersonic versions. If a theme does not appear, check the theme directory and the application's theme format/version.

## Repository layout

```text
.
├── .editorconfig
├── LICENSE
├── README.md
├── assets/
│   └── preview.png
└── themes/
    ├── gruvbox-dark/
    │   ├── red.toml
    │   ├── blue.toml
    │   └── purple.toml
    ├── gruvbox-material-dark/
    │   ├── red.toml
    │   ├── blue.toml
    │   └── purple.toml
    └── gruvbox-light/
        ├── red.toml
        ├── blue.toml
        └── purple.toml
```

## Contributing

Contributions are welcome. Keep theme names descriptive, preserve the Supersonic theme schema, and validate TOML before opening a pull request.

## License

MIT. See [LICENSE](LICENSE).
