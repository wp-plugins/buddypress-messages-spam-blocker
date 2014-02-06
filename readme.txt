=== Buddypress Messages Spam Blocker=== 
Contributors: Florian Schießl
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=NX8D8HYLP9HYS
Tags: buddypress, spam, messages
Requires at least: 3.0
Tested up to: 3.8
Stable Tag: trunk
License: GPLv2
License URI: http://www.opensource.org/licenses/GPL-2.0

This plugin will block mass mailing for the buddypress messaging system

== Description ==

If there is a user (or a bot) that signed up at your site this user can start to send messages to every other user.
I had some negative experiences with this and so I wrote a module that should help to block such a spam.

Buddypress Messages Spam Blocker introduces some restrictions to your users:

* New users can send messages only 24h after their registration, so you'll have time if bot registrations have to be removed manually

Their are also some more restrictions for mass mailings (mails that are sent to "friends" of the contact list are not included in this calculation):

* Users can send 6 messages maximum in 5 minutes
* Users can send 10 messages maximum in 10 minutes
* Users can send 20 messages maximum in 30 minutes
* Users can send 30 messages maximum in 60 minutes
* Users can send 35 messages maximum in 12 hours
* Users can send 45 messages maximum in 24 hours
* Users can send 50 messages maximum in 48 hours

Users with the capability "edit_users" (admins etc.) have no restrictions for outgoing messages

Install, activate, and it will work.

== Installation ==

1. Upload the files to the `/wp-content/plugins/buddypress-messages-spamblocker/` directory or install through WordPress directly.
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Are there some options for the parameters or are these parameters hard coded? =

At the moment they are hardcoded, you can easily chance them inside the code as you need them.

== Changelog ==

= 1.1 =
* users that have the capability "edit_users" have no restictions for outgoing messages

= 1.0 = 
* First version.
