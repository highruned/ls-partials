# page:sitemap
Generates a simple XML sitemap for use with Google, Yahoo, etc.

More information can be found [in this topic](http://forum.lemonstandapp.com/post/3576/#p3576)

## Usage

**New Partial:** page:sitemap

**page:sitemap Content:** Code found in the /src/ directory.

**New Page:** /sitemap/

**/sitemap/ Pre-action Code:**
	header("Content-Type: application/xml");

**/sitemap/ Content:**
	<? $this->render_partial('page:sitemap') ?>

**Add to .htaccess (above # All other requests comment):**
	RewriteRule sitemap\.xml$ index.php?q=/sitemap [L,QSA]
