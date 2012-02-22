## Twitterfeed Laravel bundle

## Usage

1. Put the files into the corresponding folders

2. Edit the config file and set some caching method

3. Call the library in controller / view and show in unordered list style 

```php
Twitter::timeline_list('laravelphp', 5);
```

or process as you want


```php
Twitter::timeline('laravelphp', 5); 
```