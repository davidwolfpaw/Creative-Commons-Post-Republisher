# === Creative Commons Post Republisher ===
Contributors: wolfpaw
Donate link: https://david.garden/
Tags: creative commons, licensing
Requires at least: 4.0.0
Tested up to: 6.5.4
Stable tag: 2.1.0
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

This plugin allows you to add a button to your site's posts which will display terms and licensing for Creative Commons reposting, as well as the title and content of the post for easy sharing. This is useful for sites that want to easily and clearly share their content with others.
# Creative Commons Post Republisher

|                          |                             |
| ------------------------ | --------------------------- |
| **Contributors:**        | @davidwolfpaw               |
| **Donate link:**         | https://david.garden/       |
| **Tags:**                | creative commons, licensing |
| **Requires at least:**   | 4.0.0                       |
| **Tested up to:**        | 6.5.4                       |
| **Stable tag:**          | 2.1.0                       |
| **[License](#License):** | [GPLv3 or later][gplv3]     |

This plugin allows you to add a button to your site's posts which will display terms and licensing for Creative Commons (CC) reposting, as well as the title and content of the post for easy sharing. This is useful for sites that want to easily and clearly share their content with others.

## Usage

1. Install and activate the plugin.
2. Navigate to the Creative Commons settings page under Settings in the WordPress dashboard.
3. Edit the terms text andv select the license type that you want to use as a default.
4. On individual posts, you can select a different license type to use, or set that particular post to not Creative Commons licensed.

## Changelog

### 2.1.0
* Allows plugin to function in Classic Editor as v1.4 did
* bug fixes

### 2.0.0
* Updates plugin to work with the Full Site Editor
* Plugin still works with Classic Editor
* Update required for ClassicPress or sites without Full Site Editor
* Republish button text can be changed
* Republish Terms default text updated
* Updates design of terms modal
* Displays globally set license in metabox
* Deprecated PHP updated for PHP v8.2
* WordPress comment code no longer displayed
* Shortcodes converted to HTML in Republish box

### 1.4.0
* Sets an option for CC0 No Rights Reserved
* Sets an option for CC0 Public Domain Mark

### 1.3.0
* Sets an option for defaulting to no CC license
* Adds a pot translation file

### 1.2.3
* Style for open button updated
* Copy textarea set overflow to scroll instead of hidden

### 1.2.2
* Open and Close links converted to HTML buttons
* Style for open button updated

### 1.2.1
* PHP Code Beautified
* Updating plugin for translation and internationalization

### 1.2.0
* Updated JavaScript used to not require jQuery

### 1.0.0
* First Version, wooo!

## License

* [`LICENSE`](LICENSE): [GPLv3 or later][gplv3]

[gplv3]: https://www.gnu.org/licenses/gpl-3.0.html "The GNU General Public License v3.0 - GNU Project - Free Software Foundation"

### CC license buttons

* The CC license buttons ([`assets/img/`](assets/img/)) are used
  under the Creative Commons Trademark Policy (see [Policies - Creative
  Commons][ccpolicies]).
* **The CC license buttons are not licensed under a Creative Commons
  license** (also see [Could I use a CC license to share my logo or
  trademark? - Frequently Asked Questions - Creative Commons][tmfaq]).

[ccpolicies]: https://creativecommons.org/policies
[tmfaq]: https://creativecommons.org/faq/#could-i-use-a-cc-license-to-share-my-logo-or-trademark
