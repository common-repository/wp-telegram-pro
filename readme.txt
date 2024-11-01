=== WP Telegram Pro ===
Contributors: parselearn
Donate link: https://parsa.ws
Tags: telegram, woocommerce, bot, robot, channel, notification
Requires at least: 5.0
Tested up to: 5.4
Stable tag: 2.1
Requires PHP: 5.6
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Integrate your WordPress site with Telegram

== Description ==

**Integrate your WordPress site with Telegram**

* New comments, Recovery mode, Auto core update, Users login, Register a new user notification
* Search in WordPress post types
* Send post types manually or automatically to Telegram channel
* Display Telegram channel members count with shortcode
* Connect WordPress profile to Telegram account
* Two Step Telegram bot Authentication
* Connect to Telegram with Proxy

**Integrate with E-Commerce plugins:**

* [WooCommerce](https://wordpress.org/plugins/woocommerce) – Sale products on the Telegram bot. Send product to Telegram channels. New order, Order status change, Product low/no stock, new order note notification

**Integrate with Forms plugins:**

* [Contact Form 7](https://wordpress.org/plugins/contact-form-7) and [Flamingo](https://wordpress.org/plugins/flamingo)
* [WPForms](https://wpforms.com) and [Contact Form by WPForms](https://wordpress.org/plugins/wpforms-lite)
* [Formidable Form Builder](https://wordpress.org/plugins/formidable)
* [Gravity Forms](https://www.gravityforms.com)
* [Ninja Forms](https://wordpress.org/plugins/ninja-forms)
* [Caldera Forms](https://wordpress.org/plugins/caldera-forms)
* [Everest Forms](https://wordpress.org/plugins/everest-forms)
* [HappyForms](https://wordpress.org/plugins/happyforms)
* [weForms](https://wordpress.org/plugins/weforms)
* [Visual Form Builder](https://wordpress.org/plugins/visual-form-builder)
* [Quform](https://www.quform.com)
* [HTML Forms](https://wordpress.org/plugins/html-forms)
* [Forminator](https://wordpress.org/plugins/forminator)

**Integrate with Newsletter plugins:**

* [Newsletter](https://wordpress.org/plugins/newsletter)
* [MC4WP: Mailchimp for WordPress](https://wordpress.org/plugins/mailchimp-for-wp)

**Integrate with Security plugins:**

* [Wordfence Security](https://wordpress.org/plugins/wordfence)
* [iThemes Security (formerly Better WP Security)](https://wordpress.org/plugins/better-wp-security)
* [All In One WP Security & Firewall](https://wordpress.org/plugins/all-in-one-wp-security-and-firewall)
* [Cerber Security, Antispam & Malware Scan](https://wordpress.org/plugins/wp-cerber)
* [DoLogin Security](https://wordpress.org/plugins/dologin)

**Integrate with Backup plugins:**

* [BackWPup – WordPress Backup Plugin](https://wordpress.org/plugins/backwpup)
* [BackUpWordPress](https://wordpress.org/plugins/backupwordpress)

**Integrate with other plugins:**

* [WP SMS](https://wordpress.org/plugins/wp-sms)
* [WP Statistics](https://wordpress.org/plugins/wp-statistics)
* [WP User Avatar](https://wordpress.org/plugins/wp-user-avatar)

**Translate**

* [Kurdish](https://translate.wordpress.org/locale/ckb/default/wp-plugins/wp-telegram-pro/) (Thanks [@qezwan](https://profiles.wordpress.org/qezwan/))
* [Persian](https://translate.wordpress.org/locale/fa/default/wp-plugins/wp-telegram-pro/)

== Frequently Asked Questions ==

= How to create a Telegram Bot =
[How do I create a bot?](https://core.telegram.org/bots/faq#how-do-i-create-a-bot).

= How to display Telegram channel members count =
With channel_members_wptp shortcode: `[channel_members_wptp channel="channel username" formatting="1"]`
For example: `[channel_members_wptp channel="telegram" formatting="1"]`

== Screenshots ==

1. Basic Settings
2. Channel Settings
3. WooCommerce Settings
4. Proxy Settings
5. Helps page
6. Debugs page
7. Login form with Two Step Telegram bot Authentication

== Changelog ==
= 2.1 2020-04-12 =
* Now non-administrator user can receive plugins notification
* Add Tunnel Proxy
* Control the display of posts buttons
* Fixed some bugs

= 2.0.3 2020-01-26 =
* Fixed plugin activate error

= 2.0.2 2020-01-23 =
* Fixed error in the addons

= 2.0.1 2020-01-22 =
* Fixed tags with space
* Fixed create plugin DB table
* Fixed duplicate plugin menu

= 2.0 2020-01-19 =
* Two Step Telegram bot Authentication
* Integrate with DoLogin Security plugin
* Fixed error in PHP5.*

= 1.9 2019-12-24 =
* Integrate with some plugins
* New WordPress and WooCommerce notification option
* Fixed WooCommerce "Exclude Categories" and "Exclude Display Categories" option
* Fixed the problem of encoding the text sent to the telegram

= 1.8 2019-12-05 =
* Add quick send to channel
* Connect WordPress profile to Telegram account
* WooCommerce new order and order status change notification
* Fixed comment notification
* Fixed problem displaying list of pattern tags
* Fixed warning with PHP V7.2.*

= 1.7.2 2019-08-24 =
* Fixed some bugs in PHP5.*

= 1.7.1 2019-07-25 =
* Add host info (IP/Location) to debugs page
* Fixed some bugs

= 1.7 2019-07-21 =
* Add debugs page
* Add helps page
* Cleans post excerpt from tags and unused shortcodes

= 1.6 2019-06-04 =
* New option for display channels metabox base on user role
* Add currency symbol to channel pattern tags, `{currency-symbol}`
* Fixed some bugs

= 1.5 2019-05-12 =
* Inline button for channel message
* Fixed some bugs

= 1.4 2019-05-02 =
* Delay time to send channels
* Fixed some bugs

= 1.3 2019-04-22 =
* Add proxy settings

= 1.2 2019-04-13 =
* Compatible with RTL languages
* Add custom field and terms to pattern tags
* Add if statement to pattern tags
* Admin can force update telegram keyboard

= 1.1 2019-04-06 =
* Add channel_members_wptp shortcode for display Telegram channel members count.


 == Upgrade Notice ==
