# cms:categories
Outputs an unordered list of categories.

## Usage
  <?
    $this->render_partial('shop:categories', array(
      'list_parent_class' => 'categories',
      'item_defualt_class' => 'item'
    ));
  ?>

## Options

###use_anchor_classes
> type: `bool`  
> default: `false`

*If `true`, it will output any specified anchor classes.*

---
'use_list_classes' => true,
'list_default_class' => '',
'list_parent_class' => '',
'list_parent_id' => '',
'list_child_class' => '',
'show_list_markup' => true,

'use_item_classes' => true,
'item_default_class' => '',
'item_current_class' => 'active',
'item_first_class' => 'first',
'item_last_class' => 'last',
'item_parent_class' => 'parent',
'show_item_children' => true,
'item_delimiter' => '|',
'show_item_delimiter' => false,
'show_item_parents' => false,

'use_anchor_classes' => true,
'anchor_default_class' => '',
'anchor_current_class' => 'active',
'anchor_first_class' => 'first',
'anchor_last_class' => 'last',
'anchor_parent_class' => 'parent',

'insert_before' => null,
'insert_after' => null,
'render_before' => null,
'render_after' => null,
'current_url' => null,

'parent' => null,
'child' => null,
'filter' => null,
'tree' => null,

'list' => array()
