=======
cms:category_list
=======

Outputs a unordered list of categories.

Usage
================
	<?
		$this->render_partial('shop:category_list', array(
			'parent_list_class' => 'categories',
			'item_class' => 'item'
		));
	?>

Options
================

return_output
--------

    | type: **Boolean**
    | default: **false**

Currently does nothing.

*****

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

'current_url' => null
