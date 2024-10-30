=== Login Secure ===
Contributors: rizwanabbasi
Donate link: http://rizwanabbasi.com
Tags: brute force, secure login, security, custom login url, block login url
Requires at least: 4.6
Tested up to: 5.8.1
Stable tag: 5.8.1
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html
== Try it out on your free dummy site: ==
Secure login from unauthorized users. Blocks default WordPress login URLs and require a special code in WordPress Login URL.

== Description ==
== Try it out on your free dummy site: ==
[Click Here](https://tastewp.com/new?pre-installed-plugin-slug=login-secure&redirect=options-general.php%3Fpage%3Dlogin-secure&ni=true)
Login Secure is an easy-to-use and user-friendly WordPress plugin that secures your website from unauthorized users. Blocks default WordPress login URLs and require a special code in WordPress Login URL.

After installing and activating the plugin, go to 'Settings>>Login Secure' link. Enter a unique string and click save changes.
Your WordPress login URL will be the one displayed on that page.

After storing a unique string, your default WordPress login URL will not work, even user can not log in by going to
http://example.com/wp-admin where example.com is your WordPress installation link.

== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload the plugin files to the `/wp-content/plugins/login-secure` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Use the Settings->Login Secure screen to configure the plugin
1. (Make your instructions match the desired user flow for activating and installing your plugin. Include any steps that might be needed for explanatory purposes)


== Frequently Asked Questions ==

= What will happen if I do not provide a unique string and keep that field blank? =

You will use the default behavior of WordPress for logging in. E.g, http://example.com/wp-login.php

= Will there be any extra character in my secure login URL? =

Yes, just a sign of exclamation(?) after wp-login.php
E.g if your unique string is "test" then the URL will be
http://example.com/wp-login.php?test

== Screenshots ==
1. After installing and activating the plugin, you have to go to 'Settings>Login Secure' screen.
2. Plugin's settings screen where user can add/update unique URL login string.

== Changelog ==

= 1.0.1 =
* Updated Readme file so that users can test the plugin without even installing WordPress.

* Another change.

= 1.0 =
* Initial release of the plugin

 == Upgrade Notice ==

= 1.0.1 =
* User can test the plugin without even installing WordPress and the plugin by using a ready-made preinstalled WordPress installation.


