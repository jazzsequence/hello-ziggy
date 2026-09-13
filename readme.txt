=== Hello Ziggy ===

Contributors: jazzs3quence
Donate link: https://paypal.me/jazzsequence
Tags: hello dolly, hello, david bowie, music, ziggy stardust, ziggy
Requires at least: 2.9
Tested up to: 7.1
Requires PHP: 7.0
Stable tag: 2.1.3
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Instead of "Hello Dolly", this plugin will display a random lyric from David Bowie's "Ziggy Stardust".

== Description ==

This is not just a plugin, it symbolizes the hope and enthusiasm of an entire generation-- okay, yeah, it's just a plugin. When activated you will randomly see a lyric from <cite>Ziggy Stardust</cite> in the upper right of your admin screen on every page.  All thanks goes to [Matt](http://ma.tt) for actually writing the plugin, and [David Bowie](http://www.davidbowie.com) for being Ziggy Stardust. Yes, this is just a fork of [Hello Dolly](http://wordpress.org/extend/plugins/hello-dolly/).

== Changelog ==

= Version 2.1.3 =

* Added the `Plugin URI`, `Requires at least`, `Requires PHP` and `License URI` plugin headers, none of which were present.
* Declared WordPress 2.9 as the minimum, which is when `wp_kses_post()` landed. It said 2.8.
* Tested up to WordPress 7.1.
* Fixed a double slash in the stylesheet URL.
* Releases now deploy to WordPress.org from a GitHub Action instead of by hand.

= Version 2.1.2 =

* made installable via Composer

= Version 2.1.1 =
* tested on WordPress 5.9

= Version 2.1 =

* tested on WordPress 5.0
* moved css to separate file & enqueued normally.
* refactored the main `hello_ziggy` function to use sanitization and better coding standards.

= Version 2.0 =

* finally fixed the positioning for new admin & posted on wp.org

= Version 1.5.2 =

* fork of Hello Dolly
