staffer
=======

A WordPress plugin that adds staff management and custom staff profile pages.

<h4>Description</h4>

Staffer uses custom post types for staff/employee management, allowing users to easily create and manage an onsite staff directory. Staffer works immediately with many popular WordPress themes, but also allows for custom template use and custom content wrappers. These settings make it easy to use with almost any WordPress theme.

<h4>Installation</h4>
1. Upload the \'staffer\' folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the \'Plugins\' menu in WordPres
3. Visit the Settings panel to set up Staffer.

Frequently Asked Questions
==========================
<h4>How Do I Set Up a Custom Template?</h4>

Staffer uses two main templates: archive-staff.php and single-staff.php. If these files are present within your theme directory, Staffer will load your custom files rather than the plugin's default files. So, to create a custom template, you might start by copying archive-staff.php and single-staff.php into your theme's template. Then you could proceed to customize the template to your satisfaction. Some basic HTML/PHP skills will generally be needed for this. If you aren't comfortable with this, I suggest reaching out to a competent developer. I'm also available for paid support and customization, so please contact me through my website should you need assistance.

Using some combination of custom templates and custom wrappers, Staffer should work with most any WordPress theme.

<h4>How Can I Set the Order of Staff Profiles?</h4>

For now, use a custom ordering plugin, such as Post Types Order, available in the WordPress plugin repository. I plan on adding this functionality to Staffer in the future.

<h4>How Do I Use Custom Content Wrappers?</h4>

Custom content wrappers are used when Staffer doesn't flow well with your theme. Due to the incredible diversity of WordPress themes, I've included this option for folks that find the default wrappers do not work for them. You will need to utilize Chrome's Developer Tools or a Firefox add-on like Firebug to inspect the page elements to find your theme's content wrappers. For example, here is the start of the content wrapper for the Twenty-Twelve theme:

`<div id="primary" class="site-content"><div id="content" role="main">`

And here is the end wrapper:

`</div></div>`

<h4>What Size Should the Staff Images Be?</h4>

The ideal size, as shown in the plugin screenshots, is 250x200. However a variety of image sizes will work. To preserve the formatting, make sure all your images are uniform in size, particularly if you are using the Staffer grid layout.

<h4>Where Can I Get Support?</h4>

You may seek community support within the WordPress.org forums. I will try to monitor and assist as needed. If you need immediate, hands-on, paid support, please contact me through my website: www.edwardrjenkins.com

<h4>Changelog</h4>
= 1.3 =
<br>
= November 25, 2014 =
<br>
* fixed issue with permalinks not refreshing automatically
* added full bio option
* fixed blank breadcrumbs issue
* added phone number field
* added German and Spanish translations
* fixed post per page issue
* fixed issue when pretty permalinks are disabled
* added link to main page from admin menu
* added taxonomy
* removed sidebar option
<br>
= 1.2 =
<br>
= October 11, 2014 =
<br>
* fixes custom post type conflict
= 1.1 =
<br>
= October 10, 2014 =
* Moved register_post_type to activation hook
* Added custom label field for proper title tag handling
* Added website field to profiles
* Changed <section> to <div> in single-staff.php for validation
* Added built-in wrappers for most of top 20 popular WordPress themes
= 1.0 =
* Initial release
