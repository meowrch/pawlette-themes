

<div align="center">

# 🎨 Pawlette Themes

**Official theme repository for Pawlette**

[![Issues](https://img.shields.io/github/issues/meowrch/pawlette-themes?color=bd93f9&labelColor=1C2325&style=for-the-badge)](https://github.com/meowrch/pawlette-themes/issues)
[![Stars](https://img.shields.io/github/stars/meowrch/pawlette-themes?color=9893f9&labelColor=1C2325&style=for-the-badge)](https://github.com/meowrch/pawlette-themes/stargazers)
[![License](https://img.shields.io/github/license/meowrch/pawlette-themes?color=93b9f9&labelColor=1C2325&style=for-the-badge)](./LICENSE)


[Installation](#installation) • [Available Themes](#available-themes) • [Create Theme](#creating-your-own-theme) • [Contributing](#how-to-add-your-theme)

</div>

---

## 📖 About

Pawlette Themes is a centralized repository of themes for [Pawlette](https://github.com/meowrch/pawlette), the theme manager for Meowrch. This repository hosts both official themes maintained by the Meowrch team and community-contributed themes.

### Repository Structure

- **`themes.list`** — official themes verified and maintained by the Meowrch team
- **`community-themes.list`** — community themes added via Pull Requests

## <a name="installation"></a>🚀 Installation

### Install a theme

```bash
pawlette install-theme <theme-name>
```

Example:
```bash
pawlette install-theme catppuccin-mocha
```

### List available themes in marketplace

```bash
pawlette list-store-themes
```

### Apply an installed theme

```
pawlette apply <theme-name>
```

## <a name="available-themes"></a>🎨 Available Themes

### Official Themes

- **catppuccin-mocha** — dark theme in Catppuccin Mocha style
- **catppuccin-latte** — light theme in Catppuccin Latte style

> More themes coming soon! Stay tuned 🐾

### Community Themes

Check out [`community-themes.list`](community-themes.list) for themes created by the community.

## <a name="creating-your-own-theme"></a>🛠 Creating Your Own Theme

Want to create your own unique theme for Pawlette? It's easier than you think!

### Quick Start

1. Read the [comprehensive guide](https://meowrch.github.io/en/customization/create-theme/) on creating themes
2. Study the official theme examples to understand the structure:
   - [pawlette-catppuccin-mocha-theme](https://github.com/meowrch/pawlette-catppuccin-mocha-theme)
   - [pawlette-catppuccin-latte-theme](https://github.com/meowrch/pawlette-catppuccin-latte-theme)
3. Create your theme repository
4. Package your theme as a `.tar.gz` archive
5. Create a GitHub release with the theme archive


## <a name="how-to-add-your-theme"></a>🤝 How to Add Your Theme

### Adding to community-themes.list

1. Fork this repository
2. Add your theme to `community-themes.list` in the following format:
   ```
   theme-name https://github.com/username/theme-repo/archive/refs/tags/v<X.X.X>.tar.gz
   ```
3. Make sure that:
   - The archive is accessible via direct link
   - The theme meets the [requirements](https://meowrch.github.io/en/customization/create-theme/)
   - The theme name is unique and doesn't conflict with existing themes
4. Create a Pull Request with a description of your theme

### Theme Requirements

- Correct theme file structure
- Working direct link to `.tar.gz` archive
- `theme.conf` file with required fields
- Theme screenshots in the repository (recommended)

## 📝 File Format

The `themes.list` and `community-themes.list` files use the following format:

```
theme-name https://direct-download-link/theme.tar.gz
```

**Example:**
```
catppuccin-mocha https://github.com/meowrch/pawlette-catppuccin-mocha-theme/archive/refs/tags/v1.7.tar.gz
my-awesome-theme https://github.com/username/my-theme/releases/download/v1.0/theme.tar.gz
```

## 📚 Documentation

- [Meowrch Documentation](https://meowrch.github.io/)
- [Creating a Theme](https://meowrch.github.io/en/customization/create-theme/)
- [Pawlette GitHub](https://github.com/meowrch/pawlette)
