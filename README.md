# play-modsecurity

Type below command so that you can run container.
`docker-compose up -d`

You can check whether the container which you run is working or not.

`curl -D - http://localhost/foo?testparam=thisisatestofmodsecurity`

### reference
- [docker-nginx-modsecurity](https://github.com/Fufuhu/docker-nginx-modsecurity)

- [OSS WAF(Nginx + ModSecurity 3)のDockerイメージを作ったよ](https://note.com/ryoma_0923/n/ndff9c1a58743)

- [ModSecurity 3.0 and NGINX: Quick Start Guide](https://www.nginx.com/resources/library/modsecurity-3-nginx-quick-start-guide/)

- [OWASP ModSecurity Core Rule Set](https://owasp.org/www-project-modsecurity-core-rule-set/)

