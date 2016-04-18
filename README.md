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

## License

See [LICENSE](/LICENSE) file.
