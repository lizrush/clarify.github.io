{% highlight php %}
<?php

require '../vendor/autoload.php';

$bundle = new Clarify\Bundle('my api key');
$result = $bundle->create('Dorothy and the Wizard of Oz', 'http://media.clarify.io/audio/books/dorothyandthewizardinoz_01_baum_64kb.mp3');
{% endhighlight %}