# epsilon-smart-notification

> Initiate Epsilon Smart Notification Class

	Epsilon_Smart_Notification::get_instance( array(
		'id' => 'blaskan', // An unique id, in order to save dismiss actions in db.
		'plugins' => array(
			'shortpixel-image-optimiser' => array(
				'name' => 'ShortPixel Image Optimizer',
				'description' => 'A freemium easy to use, comprehensive, stable and frequently updated image compression plugin supported by the friendly team that created it.',
				'image' => get_stylesheet_directory_uri() . '/assets/images/shortpixel.png',
			),
			'modula-best-grid-gallery' => array(
				'name' => 'Modula WordPress Photo Gallery',
				'description' => 'Modula is currently the easiest and fastest photo gallery plugin for WordPress. With its wizard you are able to build an image gallery in a few seconds, unlike many other WordPress gallery plugins.',
				'image' => get_stylesheet_directory_uri() . '/assets/images/wp-modula.jpg',
			),
		),
		
	) );