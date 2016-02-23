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

 ```
Options +FollowSymLinks
RewriteEngine on
RewriteRule (.*) http://www.yorsiteredirection.com.br/site/ [R=301,L]
 ```
where:

```
 R=301 // redirect rule
 L // declare be the last rule to be apply.
```
Reference: [Link](http://www.webhosting.uk.com/blog/301-vs-302-redirect/)
