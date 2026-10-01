# scoop-errand

[Scoop](https://scoop.sh) bucket for [errand](https://github.com/lydakis/errand)'s Windows runner.

```powershell
scoop bucket add errand https://github.com/lydakis/scoop-errand
scoop install errand
errand setup
```

To upgrade, run `scoop update errand`, then `errand setup` again.

`bucket/errand.json` is updated automatically by errand's **Publish Scoop** workflow when a stable release is published. Don't edit it by hand.
