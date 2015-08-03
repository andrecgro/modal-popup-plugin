#  Popup Plugin

Popup Plugin is a Wordpress plugin that allows you to add a beautiful modal dialog with the content of a specified page or post;

##Install

###Extracting the files

1. You can download the plugin from our Wordpress Plugin Page;
2. Extract it inside `wp-content/plugins`;
3. Activate the plugin inside the Administration Panels of your site;

###Installing from Administration Panel of your website

1. Go to `Add new Plugin` page;
2. Search for `Popup Plugin`;
3. Click `Install`;
4. Activate the plugin inside `Plugins page`;

##Usage

1. Create the page/post with the content you want to show in your modal dialog;
2. Get your page/post id ( You just need to get the number after `/?p=` in page/post permalink );
3. Create an widget or use the shortcode `<?php do_shortcode('popup-plugin[$contentID]'); ?>` in your child theme.
4. That will shows a default feature section linkable to a modal with the content ID;
