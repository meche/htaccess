# .htaccess configuration

Simple configuration for static websites

## Friendly url
 ```
RewriteEngine On
RewriteRule ^fale-conosco/?$ contatos.php [NC, L]
 ```
 where:
 
 ```
 NC // the link don't sensitive and accept uppercase and lowercase.
 L // declare be the last rule to be apply.
 ```
 
 ## Redirect Wordpress website
