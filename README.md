# Simple project setting up NGINX as  a reverse proxy and a load balancer. There are 3 servers (docker) who will receive the forwarded request from NGINX.

## Make sure to run the command inside the file "create_self_signed_cert.txt" to generate the self signed certificate. Make sure you have "openssl" installed.

## Make sure you have nginx installed. Open the file nginx.conf from your NGINX installation and replace it with the content of this project's nginx.conf file. Remember to replace the "ssl_certificate" and "ssl_certificate_key" values with your keys created above.