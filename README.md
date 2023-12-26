# moodle_custom_theme

## Moodle new theme setup:
1. Copy directory jot to /themes/ directory
2. Run this command in terminal:
```php admin/cli/upgrade.php ```
   or update plugins in web 
   
   
   
## After any updates of the theme you should run 

```php admin/cli/purge_caches.php```


## The easiest and the fastest way to add custom html to all head tags, at the start or at the end of body is go to:
> Admin account -> Site administration -> Appearance -> Additional HTML

### To add fonts use previous this point and paste:
```
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
<link href="https://fonts.googleapis.com/css2?family=Chakra+Petch:wght@500&amp;family=Lato:wght@100;400;700&amp;display=swap" rel="stylesheet">
```