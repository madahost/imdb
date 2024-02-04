# IMDB API

install 

`composer require madahost/imdb:dev-master`

how to use
```php
$imdb = new \Imdb\Title("tt01087789");
if($imdb->isReady()) {
	var_dump($imdb->title());
}
```
