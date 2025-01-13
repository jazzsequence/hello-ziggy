![ziggy stardust](https://ps.w.org/hello-ziggy/assets/banner-772x250.png?rev=660178)

# Hello Ziggy

Contributors: [jazzsequence](https://github.com/jazzsequence)  
Donate link: https://paypal.me/jazzsequence  
Tags: hello dolly, hello, david bowie, music, ziggy stardust, ziggy  
Requires at least: 2.8  
Tested up to: 5.9  
Stable tag: 2.1.2  

Instead of "Hello Dolly", this plugin will display a random lyric from David Bowie's "Ziggy Stardust".

## Description

This is not just a plugin, it symbolizes the hope and enthusiasm of an entire generation-- okay, yeah, it's just a plugin. When activated you will randomly see a lyric from <cite>Ziggy Stardust</cite> in the upper right of your admin screen on every page.  All thanks goes to [Matt](http://ma.tt) for actually writing the plugin, and [David Bowie](http://www.davidbowie.com) for being Ziggy Stardust. Yes, this is just a fork of [Hello Dolly](http://wordpress.org/extend/plugins/hello-dolly/).

### Installation

#### Via Composer

Hello Ziggy can be installed on Composer-based WordPress sites by using the following command:

```bash
composer require jazzsequence/hello-ziggy
```

#### Via Git Updater

Hello Ziggy supports [Andy Fragen's Git Updater](https://git-updater.com) method of managing plugins. 

1. Download and install [Git Updater](https://git-updater.com/git-updater/) on your WordPress site.
1. From the Git Updater admin pages, navigate to **Install Plugin** and use the following values:

**Plugin URI:** `jazzsequence/hello-ziggy`  
**Repository Branch:** `main`  
**Remote Repository Host:** `GitHub`  
**GitHub Access Token:** (optional, leave blank)

#### Via WordPress Plugin Repository
The plugin can be installed via the WordPress plugin repository, however, the version in the repository may not be the most current version. Use the standard methods of searching for and installing the plugin from the Plugins page in your WordPress dashboard.

## Changelog

### Version 2.1.2
* made installable via Composer

### Version 2.1.1
* tested on WordPress 5.9

### Version 2.1

* tested on WordPress 5.0
* moved css to separate file & enqueued normally.
* refactored the main `hello_ziggy` function to use sanitization and better coding standards.

### Version 2.0

* finally fixed the positioning for new admin & posted on wp.org

### Version 1.5.2

* fork of Hello Dolly
