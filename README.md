# README

[Lost book](http://www.xyzpub.com/en/ruby-on-rails/4.0/http_caching.html)
[Book](http://www.xyzpub.com/en/ruby-on-rails/4.0/index.html)


1. Companies show check speed
```console
 curl -I http://0.0.0.0:3000/companies/1 --header 'If-Modified-Since: Fri, 26 Apr 2019 21:08:35 GMT'
```