This repo contains files to deploy Caddy server in a docker container with Caddyfile and certs folder necessary for LetsEncrypt TLS.

Docker command to launch:  docker run -d -p 80:80 -p 443:443 -v $(pwd)/Caddyfile:/etc/Caddyfile -v $(pwd)/caddy:/root/.caddy -v $(pwd)/static_files:/srv abiosoft/caddy

Reverse proxy info:  https://medium.com/bumps-from-a-little-front-end-programmer/caddy-reverse-proxy-tutorial-faa2ce22a9c6
