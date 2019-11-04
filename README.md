### nginx-image-resizer

Example of image resizing with the help of nginx and ngx_http_image_filter_module.

Run example:
```sh
docker run --name test_resizer \
            -p 8080:80 \
            -v /path/to/images:/images:ro \
            -v /path/to/cache/:/resized_images \
            -d m1x0n/nginx-image-resizer
```
