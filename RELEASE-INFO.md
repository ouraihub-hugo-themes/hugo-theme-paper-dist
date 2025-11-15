# Hugo Paper Theme - Release Package

**Version**: 0.7.9
**Release Date**: 2025-11-15 09:12:29

## What's Included

This release package contains:
- ✅ Pre-compiled CSS (Tailwind CSS v4) in `static/css/`
- ✅ Pre-compiled JavaScript (from TypeScript) in `static/js/`
- ✅ Complete theme templates in `layouts/`
- ✅ Internationalization files in `i18n/`
- ✅ Content archetypes in `archetypes/`

**No build step required - ready to use immediately!**

## What's NOT Included

- ❌ Source files (TypeScript, Tailwind CSS source)
- ❌ Development tools (package.json, tsconfig.json)
- ❌ Build scripts and configuration
- ❌ `assets/` directory (not needed for pre-compiled theme)

**Why?** This keeps the package small and focused on what users need.

## Directory Structure

```
hugo-theme-paper-dist/
├── static/
│   ├── css/
│   │   └── main.css          # Pre-compiled CSS
│   ├── js/
│   │   └── main.js           # Pre-compiled JS
│   └── toggle-theme.js       # Theme switcher
├── layouts/                  # Theme templates
├── i18n/                     # Translations
├── archetypes/               # Content templates
├── go.mod                    # Hugo Modules config
└── README.md
```

## For Customization

If you need to customize the theme's CSS or JavaScript:

1. Fork the development repository: https://github.com/ouraihub-hugo-themes/hugo-theme-paper
2. Make your changes to the source files
3. Build using `pnpm install && pnpm build`
4. Use your custom version

## Installation & Usage

See [README.md](README.md) for detailed installation and usage instructions.
