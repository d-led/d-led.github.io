## Theme

[congo](https://jpanther.github.io/congo/docs/)

### Theme Quirk

after installing as a [hugo module](https://jpanther.github.io/congo/docs/installation/#install-using-hugo)

```bash
cp $TMPDIR/hugo_cache/modules/filecache/modules/pkg/mod/github.com/jpanther/congo/v2@v2.2.0/config/_default/*.toml config/_default
```

`module.toml` must contain afterwards:

```toml
[[imports]]
path = "github.com/jpanther/congo/v2"
```
