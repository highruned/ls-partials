===
cms:page_list
===

Outputs a unordered list of pages.

Usage
================::
	<?
		$home_page = Cms_Page::create()->find_by_url('/');

		$this->render_partial('cms:page_list', array(
		  'page_list' => array_merge(array($home_page), $home_page->navigation_subpages()),
		  'parent_list_class' => 'children',
		  'item_default_class' => 'page_item'
		));
	?>

Options
================
use_anchor_classes
--------

    | type: **Boolean**
    | default: **false**

If ``true``, it will output any specified anchor classes.

*****

'anchor_default_class' => ''

'anchor_current_class' => 'current'

'anchor_first_class' => 'first'

'anchor_last_class' => 'last'

'use_item_classes' => true

'item_default_class' => ''

'item_current_class' => 'current'

'item_first_class' => 'first'

'item_last_class' => 'last'

'show_item_children' => false

'item_delimiter' => '|'

'show_item_delimiter' => false

'use_list_classes' => true

'parent_page' => null

'parent_list_class' => ''

'parent_list_id' => ''

'child_list_class' => ''

'insert_before' => null

'insert_after' => null

'render_before' => null

'render_after' => null

'return_output' => false
Currently does nothing.
