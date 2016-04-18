# r
Custom short url redirector.

## Setup your own

Use a `_config.yml` like so:

```yaml
gems:
  - jekyll-redirect-from
```

Setup a new page `/shortname.html` to give you `yourname.github.io/r/shortname` shorturl like so:

```
---
redirect_to: /where-you-want-to-go
---
```

## Use

You can setup this redirector on its own domain using the [CNAME procedure](https://help.github.com/articles/using-a-custom-domain-with-github-pages/).

Or, like me, you can mount your `name.github.io` to a custom domain, and this site gets hosted at `name.github.io/r`.

## License

See [LICENSE](/LICENSE) file.
