# breadcrumbs
Here explain easy to use breadcrumbs in WordPress theme

Step one
================

Download breadcrumbs.php & then paste this file into inc folder 

Step Two
================

Call breadcrumbs.php in Theme Functions file

/**
 * bread crumbs
 */
//require get_template_directory() . '/inc/breadcrumbs.php'; 

Step Three
================

Use this code where you want to show breadcoms

	<div class="breadcumbs">
	<?php if (function_exists('wordpress_breadcrumbs')) wordpress_breadcrumbs(); ?>
	</div>