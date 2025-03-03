=== Simple Fast Highlighter ===
Contributors: michielve
Tags: highlighter, highlight, code, sourcecode, syntax
Requires at least: 3.0.1
Tested up to: 4.7.3
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Fast syntax highlighter written in Javascript.

== Description ==

There are other good syntax highlighter plugins, but I wanted something simple and fast and
be able to add the highlight classes with a select box in the TinyMCE editor.

I added some default languages: Javascript, PHP, Python, C, C#, VB.NET, SQL and CSS but you can
easily add other ones.

== Installation ==

1. Upload the plugin to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

See also http://michielvaneerd.github.io/simplefasthighlighter/

= Usage =

1. Select the code inside a PRE tag.
2. Select the _Code_ item in the select box, this will surround the selected area with a CODE tag.
3. Then select the language, like Javascript or PHP.

Look for an example at my blog: http://blog.michielvaneerd.nl and http://michielvaneerd.github.io/simplefasthighlighter/

== Changelog ==

= 1.0.5 =
* Tested with Wordpress 4.7.3

= 1.0.4 =
* Added custom handling to Language objects, for example to highlight Javascript regular expressions

= 1.0.3 =
* Added some es6 features to Javascript language object

= 1.0.2 =
* Removed some default styles like font and padding

= 1.0.1 =
* Added a code button
* Now you can also add the language classes directly to PRE tags

= 0.9.3 =
* Added Java also to the editor select box

= 0.9.2 =
* Updated version also in main PHP file

= 0.9.1 =
* Updated the tested up to

= 0.9 =
* Added Java language.
* Tested up to 3.9.1

= 0.8.3 =
* Fixed filenames in plugin file.

= 0.8.2 =
* Renamed files to match plugin name.

= 0.8.1 =
* Add more info to README file.
* Added a index.html file as an example.
* Removed HTML from languages: at this point it is a code highlighter and no markup highlighter.

= 0.8 =
* Plugin published.
