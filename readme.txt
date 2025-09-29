=== Hook Locator ===
Contributors: jdahir0789
Tags: actions, filters, search, debug, hook.
Requires at least: 5.0
Tested up to: 6.8
Stable tag: 1.0
Version: 1.0
Author: Jaydip Ahir
Text Domain: hook-locator
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Professional WordPress hook analysis tool for developers. Search and analyze hook usage in plugins and themes with detailed code context.

== Description ==

**Hook Locator** is the ultimate WordPress development tool for analyzing hook usage across your plugins and themes. Built for developers, it provides a professional admin interface to search, analyze, and understand WordPress hook implementations.

### Key Features

* **Advanced Hook Search** - Find any WordPress hook across all plugins and themes
* **Organized Directory Selection** - Separate dropdowns for plugins and themes with clean organization  
* **Detailed Code Analysis** - View exact file locations with highlighted code context
* **Multiple Hook Types** - Supports add_action, add_filter, do_action, apply_filters, and more
* **Professional Interface** - Clean, modern admin UI following WordPress design standards
* **Performance Optimized** - Efficient scanning with built-in safeguards and limits
* **Security First** - Proper nonce verification, sanitization, and capability checks
* **Developer Tools** - Click-to-copy code snippets, keyboard shortcuts, and export features

### Perfect For

* **Plugin Developers** - Debug hook conflicts and understand plugin interactions
* **Theme Developers** - Analyze theme hook implementations and customizations  
* **Code Auditors** - Review hook usage patterns and security implementations
* **WordPress Learners** - Understand how WordPress hooks work in real code
* **Site Maintainers** - Debug issues and optimize hook performance

### How It Works

1. **Search Interface** - Enter any hook name and select search location
2. **Instant Results** - View all matching files with line numbers and hook types
3. **Code Context** - Click any result to see highlighted code with surrounding lines
4. **Analysis Tools** - Get insights about hook types, usage patterns, and best practices

### WordPress Standards Compliant

* **PHPCS/WPCS Compatible** - Follows all WordPress coding standards
* **Secure Implementation** - Proper sanitization, nonces, and capability checks
* **Performance Optimized** - Efficient file scanning with resource limits
* **Accessibility Ready** - Keyboard navigation and screen reader compatible
* **Translation Ready** - Full internationalization support

== Installation ==

### Automatic Installation
1. Go to **Plugins > Add New** in your WordPress admin
2. Search for "Hook Locator"
3. Click **Install Now** and then **Activate**

### Manual Installation
1. Download the plugin ZIP file
2. Go to **Plugins > Add New > Upload Plugin**
3. Choose the ZIP file and click **Install Now**
4. Activate the plugin

### Getting Started
1. Navigate to **Tools > Hook Locator** in your WordPress admin
2. Enter a hook name (e.g., "init", "wp_head", "save_post")
3. Select search location (All, specific plugin, or theme)
4. Click **Search Hooks** to see results
5. Click **View Details** on any result for code analysis

== Frequently Asked Questions ==

= Does this affect my site performance? =

No! Hook Locator only runs in the WordPress admin when you actively search. There's no frontend code or background processing that affects your site's performance.

= What file types does it search? =

Hook Locator searches only PHP files (.php) since WordPress hooks are PHP-based. It automatically skips other file types for optimal performance.

= Can I search for custom hooks? =

Absolutely! Hook Locator finds any hook name you specify, including custom hooks created by plugins, themes, or your own code.

= Is it safe to use on production sites? =

Yes, Hook Locator is completely safe for production use. It only reads files and never modifies any code. All operations are restricted to users with administrator privileges.

= Does it work with multisite? =

Yes, Hook Locator works perfectly with WordPress multisite installations. Each site can use it independently to analyze their specific plugins and themes.

= Can I export the search results? =

Currently, you can copy individual code snippets to your clipboard. Future versions may include CSV/JSON export functionality based on user feedback.

= What's the difference from other hook plugins? =

Hook Locator focuses on static code analysis rather than runtime hook capture. This makes it more accurate, secure, and performant while providing deeper code insights.

---

== Screenshots ==

1. Main Search Interface – Modern search form with plugin/theme selection  
2. Search Results – Table view with file names, line numbers, and hook types  
3. Code Analysis – Highlighted view of hook usage in context  
4. Hook Type Detection – Color-coded badges for different hook functions  
5. Mobile Responsive – Works on desktops, tablets, and mobile devices  

---

== Changelog ==

= 1.0.0 =
* Initial release with full hook scanning and analysis
* Plugin and theme directory dropdowns with optgroups  
* Improved code highlighting with better contrast  
* Secure coding with nonce checks and sanitization  
* Fully WordPress coding standards compliant (PHPCS/WPCS)  
* Optimized file scanning with smart resource management  
* Professional admin UI with WordPress styling  

---

== Advanced Usage ==

### Keyboard Shortcuts
* **Ctrl/Cmd + K** – Focus search input  
* **Ctrl/Cmd + Enter** – Run search  
* **Escape** – Clear search input  
* **Click snippets** – Copy to clipboard  

### Supported Hook Types
* `add_action()`  
* `add_filter()`  
* `do_action()`  
* `apply_filters()`  
* `remove_action()`  
* `remove_filter()`  
* `has_action()`  
* `has_filter()`  

---

== Developer Information ==

* **Code Standards** – 100% PHPCS/WPCS compliant  
* **Secure** – Proper validation, sanitization, and capability checks  
* **Performance** – Smart scanning, resource limits, and memory management  
* **Accessibility** – Screen reader and keyboard navigation support  
* **Internationalization** – Fully translation ready  

---

== Privacy ==

* No personal data collection  
* No external API requests  
* No analytics, tracking, or cookies  
* Admin-only usage  

---

== Support ==

Need help?  

* WordPress.org support forums  
* Inline documentation and tooltips in the admin panel  
* GitHub issues (coming soon)

Hook Locator is actively maintained and tested with the latest WordPress releases. We welcome feedback and feature requests!  
