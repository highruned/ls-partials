# cms:image_gallery
Outputs a gallery containing one large image, and thumbnails below.

## Usage
	<? $this->render_partial('cms:image_gallery', array('list' => $product->images)) ?>
	
## Options
### thumb_width
#### return_output
> type: `Integer`  
> default: `50`
*The width of each thumbnail.*
---
### thumb_height
> type: `Integer`  
> default: `50`
*The height of each thumbnail.*

'fullsize_width' => 250,

'fullsize_height' => 250,

'list' => array()
