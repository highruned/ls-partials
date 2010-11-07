# tool:combine_resources
Combines resources (CSS, JS) into a cached file.

## Usage
	<link href="<?= root_url($this->render_partial('tool:combine_resources', array(
		'type' => 'css',
		'files' => array(
		'/resources/3rd/ls_frontend.css',
		'/resources/3rd/grid-960-16.css',
		'/resources/3rd/form.css',
		'/resources/css/main.css'
	)))) ?>" rel="stylesheet" media="screen" />

	<script src="<?= root_url($this->render_partial('tool:combine_resources', array(
		'type' => 'js',
		'files' => array(
		'/resources/3rd/jquery-1.4.2.min.js',
		'/resources/3rd/ls_frontend.js',
		'/resources/js/main.js'
	)))) ?>"></script>
