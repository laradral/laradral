Laradral
========

To install, get the code, save it into bundles/laradral.
To the bundles.php file in the application folder you add the following to the return array at the end.
```'laradral' => array('auto' => true, 'handles' => 'laradral'),

It will look something like this:
	return array(
 		'docs' => array('handles' => 'docs'),
		'laradral' => array('auto' => true, 'handles' => 'laradral'),
	);