# url Amigável

Simples configuração para sites estáticos contendo URL's amigáveis com .htaccess

### o .htaccess
 ```
RewriteEngine On
RewriteRule ^fale-conosco/?$ contatos.php [NC, L]
 ```
 Onde:
 
 ```
 NC //o link não é mais sensitivo, aceitará maíusculo e minúsculo.
 L // declara ser a última regra a ser aplicada.
 ```
 