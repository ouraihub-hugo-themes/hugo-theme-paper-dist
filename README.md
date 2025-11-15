# Hugo Paper Theme - Distribution Package

This is the **pre-compiled distribution** of Hugo Paper Theme for use with Hugo Modules.

**All CSS and JavaScript are pre-compiled. No build step needed!**

## What's Included

- ✅ Pre-compiled CSS (Tailwind CSS v4) in `static/css/`
- ✅ Pre-compiled JavaScript (from TypeScript) in `static/js/`
- ✅ Complete theme templates in `layouts/`
- ✅ Internationalization files in `i18n/`
- ✅ Ready to use immediately - no build tools required!

## What's NOT Included

- ❌ Source files (TypeScript, Tailwind CSS source)
- ❌ Development tools (package.json, tsconfig.json, etc.)
- ❌ Build scripts and configuration

**Why?** This keeps the distribution package small and focused on what users need.

## Installation

### Option 1: Hugo Modules (Recommended)
```toml
[module]
  [[module.imports]]
    path = "github.com/ouraihub-hugo-themes/hugo-theme-paper-dist"
```

```bash
hugo mod get -u
hugo server
```

### Option 2: Direct Clone
```bash
git clone https://github.com/ouraihub-hugo-themes/hugo-theme-paper-dist.git themes/hugo-theme-paper
```

### Option 3: Use Starter Template (Easiest)
```bash
git clone https://github.com/ouraihub-hugo-themes/hugo-theme-paper-starter.git my-blog
cd my-blog
hugo mod get -u
hugo server
```

## For Customization

If you need to customize the theme's CSS or JavaScript:

1. **Fork the development repository**: https://github.com/ouraihub-hugo-themes/hugo-theme-paper
2. **Make your changes** to the source files
3. **Build** using `pnpm install && pnpm build`
4. **Use your custom version**

## For Development

Want to contribute to the theme? Visit the development repository:
https://github.com/ouraihub-hugo-themes/hugo-theme-paper

## Features

- 🎨 Minimal and responsive design
- 🌓 Dark mode support
- 🔍 Built-in search functionality
- 🌐 Multi-language support (English/Chinese)
- ⚡️ Fast performance
- ♿️ Accessibility support (WCAG 2.1 AA)
- 🎯 SEO optimized
- 📱 Mobile-first design

## Documentation

- [User Guide](https://github.com/ouraihub-hugo-themes/hugo-theme-paper-starter/blob/master/docs/USER_GUIDE.md)
- [Changelog](https://github.com/ouraihub-hugo-themes/hugo-theme-paper/blob/master/docs/CHANGELOG.md)
- [Theme Documentation](https://github.com/ouraihub-hugo-themes/hugo-theme-paper)

## Version

See [RELEASE-INFO.md](RELEASE-INFO.md) for version details.

## License

MIT License - see [LICENSE](LICENSE) for details.
