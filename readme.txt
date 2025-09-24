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

Find, search, and debug WordPress hooks instantly. A powerful developer tool to analyze actions, filters, and custom hooks in plugins and themes.

== Description ==

Search and debug WordPress hooks with ease. Analyze actions & filters in plugins and themes using a fast, secure developer tool.

### Why Use Hook Locator?

* **Find WordPress hooks instantly** – Search any hook name (`init`, `wp_head`, `save_post`, or custom hooks)
* **Analyze plugins and themes** – Organized dropdowns for scanning specific directories
* **Debug faster** – View exact file paths, line numbers, and code context with highlighting
* **Optimize performance** – Detect unnecessary or conflicting hooks
* **Improve code quality** – Ensure proper usage of actions and filters
* **Developer-friendly UI** – Modern, professional, and follows WordPress admin design standards

### Key Features

* **Advanced Hook Search** – Quickly find hooks in plugins, themes, or the entire site  
* **Detailed Code Analysis** – Highlighted code snippets with surrounding context  
* **Multiple Hook Types** – Detects `add_action`, `add_filter`, `do_action`, `apply_filters`, and more  
* **Secure & Reliable** – Nonce verification, sanitization, and admin-only access  
* **Performance Optimized** – Smart scanning with limits to prevent timeouts  
* **Export & Copy Tools** – Copy code snippets or export results for documentation  
* **Accessibility Ready** – Works with keyboard navigation and screen readers  
* **Translation Ready** – Full internationalization support

### Perfect For

* **Plugin Developers** – Debug hook conflicts and ensure compatibility  
* **Theme Developers** – Analyze theme customization and hook usage  
* **Auditors & Security Reviewers** – Check for unsafe or inefficient hook usage  
* **WordPress Learners** – Understand how hooks work in real-world code  
* **Site Maintainers** – Troubleshoot issues and optimize performance  

### How It Works

1. Go to **Tools > Hook Locator** in your WordPress admin  
2. Enter a hook name (e.g. `init`, `wp_head`, `save_post`)  
3. Select a directory (all plugins, a specific plugin, or a theme)  
4. Click **Search Hooks**  
5. View results with file paths, line numbers, and hook types  
6. Click any result for detailed highlighted code context  

---

### Debug WordPress Hooks with Ease

Finding hooks in large WordPress sites can be overwhelming. Hook Locator gives developers a **fast, reliable, and professional way** to understand and debug how actions and filters are used—making development, optimization, and troubleshooting much easier.

---

== Installation ==

### Automatic Installation
1. In WordPress admin, go to **Plugins > Add New**  
2. Search for **Hook Locator**  
3. Click **Install Now** and then **Activate**

### Manual Installation
1. Download the plugin ZIP file  
2. Go to **Plugins > Add New > Upload Plugin**  
3. Upload the ZIP and click **Install Now**  
4. Activate the plugin  

### Getting Started
1. Go to **Tools > Hook Locator**  
2. Enter a hook name to search  
3. Select plugins, themes, or all directories  
4. Review results with file paths and code context  

---

== Frequently Asked Questions ==

= How do I find all hooks in a WordPress plugin? =
Simply choose the plugin from the dropdown, leave the search input blank, and Hook Locator will scan and list all actions and filters inside that plugin.

= Can I use Hook Locator to debug custom hooks? =
Yes. It works with both core WordPress hooks and custom hooks defined by plugins, themes, or your own code.

= Does Hook Locator slow down my site? =
No. The plugin only runs in the admin panel when you perform a search. It does not load on the frontend and does not affect site performance.

= What is the difference between Hook Locator and runtime hook loggers? =
Hook Locator performs **static code analysis**. It scans the source code to detect all hook references, even those that might not run during a specific request. This makes it more complete and reliable compared to runtime loggers.

= Can it help me fix plugin conflicts? =
Yes. By showing you where hooks are added or triggered, Hook Locator helps identify conflicts between plugins or themes so you can resolve issues faster.

= Does Hook Locator work with WordPress multisite? =
Yes. It works on multisite installations. Each site can independently use Hook Locator to analyze its plugins and themes.

= Is Hook Locator safe to use on production sites? =
Absolutely. It only **reads** files; it never modifies code. All operations are restricted to administrators.

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
