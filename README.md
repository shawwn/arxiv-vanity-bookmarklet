# arxiv-vanity-bookmarklet

A bookmarklet for [arxiv-vanity.com](https://arxiv-vanity.com). It turns arxiv PDFs into websites, making them easier to read when you're in bed. (Does anybody but me use their laptop in bed? Anyway...)

# Install

Go here: https://arxiv-vanity-bookmarklet.vercel.app/

# Details

I used https://mrcoles.com/bookmarklet/ to create the bookmarklet with this code:

```js
window.location=window.location.toString().replace(/arxiv\.org/,'arxiv-vanity.com').replace(/\/(pdf|abs)\//,'/papers/').replace(/[.]pdf$/,'')
```

# Contact

[@theshawwn](https://twitter.com/theshawwn) (DMs open!)
