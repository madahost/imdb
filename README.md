# IMDB API
This PHP library enables you to scrape data from IMDB.com.

install 
```php
composer require madahost/imdb:dev-master
```
how to use
```php
$imdb = new \Imdb\Title("tt01087789");
if($imdb->isReady()) {
	$title = $imdb->title();
}
```

For persons:
```php
$name = new \Imdb\Name("0000154");
$name = $name->name();
$nickname = $name->nickname();
```

For Calendar:
```php
$calendar = new \Imdb\Calendar();
$releases = $calendar->comingSoon();
```
