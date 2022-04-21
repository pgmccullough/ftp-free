# ftp-free
A Wordpress plugin for adding/deleting template files.

== Description ==

WP-Admin lets us upload and create new posts, pages, media, and more, so why do we have to log into our FTP or hosting provider's file manager every time we need to create a new theme template file? This simple plugin adds a simple, non-invasive form under existing theme files in the theme editor. Type in a name for the template file, click the submit button, and you're set!

== Installation ==

1. Upload `FTP-Free.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. The next time you're in the theme editor, you'll see underneath the list of current template files and stylesheets a space to type in a new template name.  Give it one (i.e. "Donations Page") and click "Create File".  The plugin will create a clean file name (i.e. "donations-page.php") using the words you typed in as the template name, and you'll be taken right to it, ready to code without ever having to leave your web browser!

== Screenshots ==

1. Creating a new theme template file

== Changelog ==

= 3.0 =
* Fixed inability to delete template files in subdirectories.
* Shows a list of pages using a given template file. 

= 2.0 =
* Will now add a number to the end of a new file with the same name as an existing one.  Would previously overwrite.
* Added ability to delete template files.

= 1.0 =
* Initial release.
