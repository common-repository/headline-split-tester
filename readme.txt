=== Plugin Name ===
Contributors: bhalliburton, peterbessman
Donate link: http://www.cogmap.com/
Tags: split test, A/B testing, headlines
Requires at least: 3.0.1
Tested up to: 3.0.1
Stable tag: 0.2

Headline Split Tester allows you to have two competing headlines for blog posts. They are randomly shown until one headline wins.

== Description ==

This plug-in allows you to enter an alternate headline for every post on your blog.  The headlines are then randomly alternated on your website until a certain number of "headline views" has been reached.  At that point, a "winning" headline (as determined by the number of people that have clicked on each headline to date) is determined and that headline is shown going forward.

== Installation ==

Installation is easy

1. Upload the `headline-split-test` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Enter alternate headlines in the alternate headline section whenever you create a new blog post
1. If you want to change our test for statistical significance, you can edit that in the "Headline Split Tester" options under the Settings menu.

This sometimes conflicts with social media tracking systems that (foolishly) use things like the Post title rather than the GUID to track activity around a post. If this is a problem, go into the settings page in your admin screen and you can configure it to not use the alternate headline on the page, only on the link to the page. This means that when a post wins, you would be best served by changing the post title, although that might mess up your social media mojo as well. Alas.

== Frequently Asked Questions ==

= How does it test for statistical significance? =

We track how many times headlines are shown and how many times each headline is clicked.  When a headline has been shown enough, the headline with the most clicks wins.

= That sucks! =

Yeah, but it is better than some alternatives. Feel free to submit patches.

== Changelog ==

= 0.2 =
* Added new code to allow people to only show the primary headline on the blog post page if they want, to keep from breaking social media analytics platforms that were poorly designed.

= 0.1 =
* Initial Release.

== Upgrade Notice ==

= 0.2 =
We made it so that this plugin does not break social media analytics tools, in response to user feedback.

= 0.1 =
If you aren't split testing your headlines in your blog, you should be.

