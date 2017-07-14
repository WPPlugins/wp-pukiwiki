=== WP PukiWiki ===
Contributors: kenwakita
Tags: formatting, post, wiki
Requires at least: 1.5
Tested up to: 2.2.2
Version: 0.2
Stable tag: trunk

WP PukiWiki allows the WordPress author to write his/her articles using a PukiWiki-style light-weight syntax, instead of HTML.

== Description ==

PukiWiki is a PHP-based Wiki.  WP PukiWiki allow the WordPress author to use PukiWiki-style Wiki syntax in writing his/her posts and pages.  PukiWiki features headings, quotations, lists of various types, preformatted texts, images, footnotes, hyperlinks, smileys, and many others.  Visit my [sample page](http://www.is.titech.ac.jp/~wakita/wordpress/en/wp-pukiwiki/).

== Requirements ==

* Working PukiWiki system accessible from the Internet.
* WP PukiWiki: WP PukiWiki uses PHP's Curl API.  Turn it on if this feature is missing on your site.

== Installation ==

1. Setup `PukiWiki` and make it accessible via http from your WordPress hosting server.  `PukiWiki` can be obtained from [PukiWiki official site](http://pukiwiki.sourceforge.jp/?About%20PukiWiki).  If you already have a running `PukiWiki` you can use that site.  WP PukiWiki uses a PukiWiki system to translate Wiki syntax to HTML but WP PukiWiki does not modify PukiWiki at all.  Therefore, it is safe to use your existing PukiWiki system.
1. Obtain [wp-pukiwiki.zip](http://downloads.wordpress.org/plugin/wp-pukiwiki.zip) and unzip it.  A folder/directory named `wp-pukiwiki` appears.
1. Open `wp-pukiwiki.php` with a text editor and modify the definition for `WPPW_URL` so that it points to the URL of your `PukiWiki` site.
1. Upload the `wp-pukiwiki` folder/directory to the `/wp-content/plugins/` directory of your WordPress hosting server.
1. Activate the  plugin.

== Screenshots ==

1. You can use PukiWiki-style syntax within a block enclosed by &lt;pukiwiki&gt;-and &lt;/pukiwiki&gt;-tags.
1. The above example produces this page view.

== Frequently Asked Questions ==

= Can I use WP PukiWiki on WordPress Mu? =

Unfortunately no.  I attempted to use WP PukiWiki on WordPress Mu and found that its security mechanism interferes with WP PukiWiki.  Now I am trying to find workarounds.

= Can I use PukiWiki's *** feature? =

There are several PukiWiki features that are missing from WP PukiWiki.

- Online viewer
- WikiNames (WikiName, BracketName, InterWiki)
- Entities (Page name entities, date entities)

== How to Use WP PukiWiki ==

Surround part of your writing with &lt;pukiwiki&gt;-tag and &lt;/pukiwiki&gt;-tag and use PukiWiki-style syntax within such surrounded parts.  Within the pukiwiki blocks, you can use [PukiWiki syntax](http://pukiwiki.sourceforge.jp/?About%20PukiWiki "the PukiWiki document").  I hope my [sample page](http://www.is.titech.ac.jp/~wakita/wordpress/en/wp-pukiwiki/) serves you as a good starting point.
