=== Plugin Name ===
Contributors: Rene Schmidt, Emre Odabas
Tags: pagerank, follow, nofollow
Requires at least: 2.7
Tested up to: 2.7
Version: 0.2

== Description ==

Checks commentator's website PageRank and removes nofollow attribute if its PageRank is higher than or equal to your website's PageRank.

Purpose of this plugin is to overcome the bias caused by NoFollow. NoFollow should be used carefully to implicitly reduce comment spam that has not been filtered (e.g. Akismet) and to prevent useless internal pages (Usage Terms and such) from harming your blog's PageRank.

The point is, many blogs apply NoFollow to ALL the web links of comment authors. This is not what NoFollow should be used for. But I do not expect bloggers to completely remove NoFollow as it may harm their PageRank. In order to break this vicious catch-22, this plugin removes NoFollow when the blog does not outrank the linked website.

Wikipedia (it's not a blog though) uses NoFollow in a totally perverted way: ALL links to sites carrying important further information get NoFollowed. 

See http://www.google.com/corporate/tech.html for more information on PageRank.

PS: PageRank values may fluctuate violently and suddenly. We all are at the mercy of Google in this regard. And there are other factors that are more important than PageRank. But it is not insignificant either.

Based on GooglePR by Emre Odabas.

Requirements: PHP5, Wordpress 2.7, CURL, write access to /tmp

Attention: This is alpha grade software. Please report any bugs or suggestions to rene@reneschmidt.de, thank you.

See http://www.reneschmidt.de/veroeffentlichungen/followpagerank/ for further information.

PLEASE: if you have problems using this alpha software, please send an email to rene@reneschmidt.de with a detailed problem description. Thank you.

== Installation ==

1. Upload followpagerank.php to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

