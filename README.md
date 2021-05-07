# alist-cdn
Alist static resources - jsDelivr CDN

## Nginx 配置：

```
    sub_filter                 /static https://cdn.jsdelivr.net/gh/sbwml/alist-cdn@v1.0.4/static;
    sub_filter_last_modified   on;
    sub_filter_once            off;
```
