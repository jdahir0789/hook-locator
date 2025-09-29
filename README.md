# 🔍 Hook Locator – WordPress Hook Analysis Plugin

[![WordPress Tested](https://img.shields.io/badge/WordPress-6.8-blue.svg)](https://wordpress.org/plugins/hook-locator/)  
[![License: GPL v2](https://img.shields.io/badge/License-GPLv2%2B-green.svg)](https://www.gnu.org/licenses/gpl-2.0.html)  
[![PHP](https://img.shields.io/badge/PHP-7.4%2B-orange.svg)](https://www.php.net/)  

**Hook Locator** is a professional **WordPress developer tool** that helps you **search, debug, and analyze WordPress hooks** across plugins and themes.  
With an intuitive UI, it highlights hook usage (`add_action`, `add_filter`, `do_action`, etc.) with file paths, line numbers, and code context.  

📦 **Plugin URL:** https://wordpress.org/plugins/hook-locator/

---

## ✨ Features

- 🔍 **Advanced Hook Search** – Instantly find any WordPress hook  
- 📂 **Plugin & Theme Directory Support** – Organized dropdown selection  
- 🧑‍💻 **Code Context Viewer** – Highlighted PHP lines around hook usage  
- 🏷 **Multiple Hook Types** – Supports `add_action`, `add_filter`, `do_action`, `apply_filters`, etc.  
- 🎨 **Modern Admin UI** – Clean WordPress-native design  
- ⚡ **Performance Optimized** – Smart scanning with safeguards  
- 🔒 **Security First** – Nonce checks, sanitization, capability checks  
- 🛠 **Developer Tools** – Click-to-copy snippets, keyboard shortcuts  

---

## 🚀 Installation

Clone into your WordPress plugins directory:

```bash
cd wp-content/plugins
git clone https://github.com/jdahir0789/hook-locator.git hook-locator
```

Or install manually:

1. Download the ZIP from GitHub.  
2. Upload to `wp-content/plugins/hook-locator`.  
3. Activate via **WordPress Admin > Plugins**.  

---

## 🎯 Usage

1. Navigate to **Tools → Hook Locator** in the WP Admin.  
2. Enter any hook name (e.g., `init`, `wp_head`, `save_post`).  
3. Choose where to search (all plugins, a specific plugin, or theme).  
4. Click **Search Hooks**.  
5. View file location, line number, and code snippet with highlighted hook usage.  

---

## 👨‍💻 Developer Info

- 100% [WordPress Coding Standards](https://github.com/WordPress/WordPress-Coding-Standards) compliant  
- Secure implementation with sanitization + nonces  
- Works with PHP `7.4+` and WordPress `5.0+`  
- Optimized for performance and large codebases  
- Translation ready  

---

## 🛡 Privacy

- ✅ No tracking  
- ✅ No external API calls  
- ✅ Admin-only functionality  

---

## 🤝 Contributing

Pull requests are welcome!  
Please open an issue first to discuss proposed changes.  

1. Fork the repo  
2. Create your feature branch (`git checkout -b feature/my-feature`)  
3. Commit changes (`git commit -m 'Add my feature'`)  
4. Push to the branch (`git push origin feature/my-feature`)  
5. Open a Pull Request  

---

## 📜 License

Distributed under the [GPL v2 or later](https://www.gnu.org/licenses/gpl-2.0.html) license.  

---

## 🔗 Links

- [WordPress Plugin Directory](https://wordpress.org/plugins/hook-locator/)  
- [Report Issues](https://github.com/jdahir0789/hook-locator/issues)  

---

⭐ If this plugin helps you debug hooks faster, **star the repo** to support development!
