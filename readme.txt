=== PageView ===
Contributors: Transiz
Tags: routes, transport, cargo, embed, iframe, transiz
Requires at least: 2.5
Tested up to: 4.0
Stable tag: trunk

Insert an iframe that displays company routes from http://transiz.com.

== Description ==

TransizRoutes is a plugin that will display the routes posted by a company on the freight exchange site http://transiz.com. This is achieved with the use of an iframe.

To use:

`[transizroutes company=%company_id%]`

Optional arguments:

* company = The company ID (from your company page on Transiz)
* lang = The language of the plugin. Available: "bg", "cn", "de", "en", "es", "fr", "hu", "it", "pl", "pt", "ro", "ru", "sp", "tr" (default "en")
* theme = The theme of the plugin. Available: "alizarin", "belizehole", "carrot", "concrete", "emerald", "nephritis", "orange", "pomegranate", "river", "silver", "sunflower", "wetasphalt", "wisteria" (default "belizehole")
* width = Width of plugin, in px or % (default 100%)
* height = Height of plugin, in px or % (default 500px)

== Installation ==

The plugin is simple to install:

1. Download `transizroutes.zip`
1. Unzip
1. Upload `transizroutes` directory to your `/wp-content/plugins` directory
1. Go to the plugin management page and enable the plugin
1. Place `[transizroutes company=%company_id%]` in your templates

== Documentation ==

Full documentation can be found on the [transizroutes](http://plugins.transiz.com/) page.

== Changelog ==

= 1.0   =
* First version