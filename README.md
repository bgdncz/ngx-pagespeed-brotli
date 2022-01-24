# What is this?
A docker image of Nginx compiled with the brotli and pagespeed modules.

## Distribution
GitHub will package a new image on every commit. It is available through `docker pull ghcr.io/boghison/nginx:latest`.

## Special note
`pagespeed HttpCacheCompressionLevel 0;` is required to use the pagespeed module with brotli.
