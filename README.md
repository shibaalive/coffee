# coffee
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://shibaalive.github.io/coffee/index.html$1 [R,L]
