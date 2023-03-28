# test
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://doug911.github.io/test/index.html$1 [R,L]
