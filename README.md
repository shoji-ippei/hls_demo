```bash
docker run --rm -p 8080:80 -it -v $(pwd)/:/usr/local/apache2/htdocs/ -v $(PWD)/my-httpd.conf:/usr/local/apache2/conf/httpd.conf httpd
```