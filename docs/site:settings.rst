=======
site:settings
=======

Returns an array of settings to use throughout templates, partials, and pages.

Usage
================

code-block:: php

	<?
		$charset = $this->render_partial('site:settings')->charset;
		$meta_description = strlen(h($this->page->description)) > 0 ? h($this->page->description) : $this->render_partial('site:settings')->default_meta_description;
		$meta_keywords = strlen(h($this->page->keywords)) > 0 ? h($this->page->keywords) : $this->render_partial('site:settings')->default_meta_keywords;
	?>
	
	<meta charset="<?= $charset ?>" />
	<meta name="description" content="<?= $meta_description ?>" />
	<meta name="keywords" content="<?= $meta_keywords ?>" />
