=== WP Grade Comments ===
Contributors: boonebgorges
Tags: comments, grade, course, privacy
Requires at least: 4.0
Tested up to: 4.4
Stable tag: 1.0.1
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

WP Grade Comments makes it easy for instructors who use WordPress in a course setting to give private feedback and/or grades to post authors, all without leaving the familiar commenting interface.

== Description ==

When reading posts while logged in as an Administrator, the comment reply form will contain two additional checkboxes:

1. "Make this comment private" - When checked, only site Administrators and the author of the current post will be able to see the comment. Threaded to private comments, whether left by an admin or by the post author, are always private as well.
1. "Add a grade" - When checked, a Grade field will appear. Grades can appear in private or public comments, while the grade itself will always be private (visible only to the Administrator and the post author). Grades are also visible to administrators as a new column in Dashboard > Posts.

This plugin was developed for the [https://openlab.citytech.cuny.edu](City Tech OpenLab).

== Installation ==

1. Install and activate from Dashboard > Plugins.
2. That's it.

== Screenshots ==

1. Comment display form. Only administrators see this form.
2. Grades are always private, even in public comments.
3. Grades are visible on Dashboard > Posts.

== Changelog ==

= 1.0.2 =
* Ensure that comment privacy is respected for trashed comments
* Prevent non-admins from editing comments that are private or contain grades, even when they are the post author
* Ensure that comment privacy is respected in feeds
* Ensure that all private comments are visible to all administrators, not just the comment author

= 1.0.1 =
* Fix name of plugin in readme header

= 1.0.0 =
* Initial release
