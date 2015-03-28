# numerous-php
Quick and Dirty PHP [Numerous](http://numerousapp.com/) API client (not complete).

##Example

``` php
<?php

$n = new GX\Numerous('YOUR API KEY HERE');

// Update a metric's units
$n->updateMetric('12345', array(
	'units' => 'meters'
));

// Add comment to metric
$n->createInteraction('12345', array(
	'commentBody' => 'this is my comment'
));

// Update a metric's value
$n->createEvent('12345', 15)

// List all metrics
echo $n->metrics();
```

##License

This work is licensed under a MIT license.
Feel free to fork, extend, improve, etc. But please include a proper attribution.
