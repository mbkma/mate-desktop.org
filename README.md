# MATE Desktop Website

Official website for the MATE Desktop Environment: https://mate-desktop.org

## Built With

- [Hugo](https://gohugo.io/) - Static site generator
- [Hextra](https://github.com/imfing/hextra) - Hugo theme

## Development

### Prerequisites

- Hugo extended version >= 0.146.0

### Local Development

```bash
hugo serve
```

The site will be available at http://localhost:1313

### Build

```bash
hugo
```

Output will be in the `public/` directory.

## Multilingual Support

The site supports multiple languages:
- English (default)
- Deutsch
- Español
- Italiano
- 日本語
- Български
- Català
- 简体中文
- 繁體中文

Translations are managed via filename suffixes (e.g., `_index.de.md` for German).

## License

Content is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
