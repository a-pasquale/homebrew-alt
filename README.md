homebrew-alt
============


nginx with cache purging
------------------------

To use this homebrew formula do:

Download the nginx cache_purge module from http://labs.frickle.com/nginx_ngx_cache_purge/
and unzip it to /usr/src/ngx_cache_purge-1.6

Then

$ brew tap a-pasquale/alt

$ brew unlink nginx

$ brew install a-pasquale/alt/nginx --with-cachepurge

Happy purging!
