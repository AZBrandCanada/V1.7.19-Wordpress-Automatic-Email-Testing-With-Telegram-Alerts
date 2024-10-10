=== Automatic Email Testing With Telegram Alerts ===
Contributors: AZBrand.ca
Tags: email, telegram, logging, scheduling, notifications
Requires at least: 5.0
Tested up to: 6.6.2
Stable tag: 1.7.19
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin allows you to schedule hourly emails and log results. Admins can send manual tests and receive Telegram notifications on failures.

== Description ==

Automatic Email Testing With Telegram Alerts is a WordPress plugin designed to help you schedule hourly emails, log their success or failure, and receive instant notifications via Telegram if any emails fail to send.

Features:
- Schedule 6 hour emails.
- Log email results to a file.
- Send test emails manually.
- Receive Telegram notifications on email failures.

== Installation ==

1. Upload the zip file to `/wp-content/plugins/` directory and unzip it.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Configure the settings by navigating to `Settings` > `Email Scheduler`.

== Third-Party API Usage ==

This plugin uses the Telegram API (api.telegram.org) to send notifications. For more information on their API, please visit their [official documentation](https://core.telegram.org/bots/api).

== Frequently Asked Questions ==

= How do I configure the plugin? =

Go to `Settings` > `Email Scheduler` and enter the email address, Telegram Bot ID, and Chat ID.

= What happens if an email fails to send? =

You will receive a Telegram notification detailing the failure.

= Can I send a test email? =

Yes, you can send a test email from the plugin settings page.

== Changelog ==

= 1.7.19 =
* Updated JavaScript to correctly calculate the time difference between current UTC time and next email send time.
* Added a clear indication when an email is currently being sent.
* Improved the display format of current time and countdown timer.
* Added custom classes for HTML and JavaScript elements.

= 1.7.18 =
* Improved internationalization: avoided using variables or defines as text, context, or text domain parameters.
* Documented use of third-party API (api.telegram.org).
* Updated to use `wp_enqueue` commands for better script management.
* Created unique prefixes for generic function/class/define/namespace/option names.
* Updated transient prefixes.

= 1.7.17 =
* Added new functionality to handle edge cases in email scheduling.
* Improved error logging for better diagnostics.
* Enhanced security features to protect against potential vulnerabilities.

= 1.7.16 =
* Updated the license information to include CC BY-ND 4.0 details.

= 1.7.15 =
* Removed email from the public log.

= 1.7.14 =
* Added nonce verification to the form for improved security.
* Sanitized user input to prevent potential security issues.
* Updated UTC time handling for proper log file calculations.

= 1.0 =
* Initial release.

== Upgrade Notice ==

= 1.7.19 =
This update includes JavaScript improvements for time calculations, better display formats, and the addition of custom classes for HTML and JavaScript elements.

= 1.7.18 =
This update includes improvements to internationalization, documentation of third-party API usage, script management, and security enhancements.

= Advanced Alerts =
For advanced alerts, visit [this link](https://github.com/AZBrandCanada/WordPress-Automatic-Email-Testing-With-Telegram-Advanced-Alerts-Serverside) to use the script serverside to monitor the log files of multiple websites for high availability.
