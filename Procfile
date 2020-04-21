dockergen: docker-gen -watch -notify "nginx -s reload" /app/nginx.tmpl /etc/nginx/conf.d/default.conf
dockergen: docker-gen -watch -notify "nginx -s reload" /app/nginx-stream.tmpl /etc/nginx/root.conf.d/streams.conf
nginx: nginx
