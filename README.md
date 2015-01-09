# numerous-php
Quick and Dirty PHP [Numerous](http://numerousapp.com/) API client (not complete).
Feel free to fork and extend.

##Example

``` php
<?php

$n = new GX\Numerous('YOUR API KEY HERE');

$n->updateMetric('12345', array(
	'units' => 'meters'
));

$n->createInteraction('12345', array(
	'commentBody' => 'this is my comment'
));

echo $n->metrics();
```
