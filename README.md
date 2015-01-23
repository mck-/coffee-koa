# Dev fork

This used to be a fork with generators, they are now part of the main repo, so you should just use that before the next release:


```bash
npm install jashkenas/coffee-script
node_modules/coffee-script/bin/coffee someFile
```

They are implicit, so just rewrite `-->` to `->` and if you don't have a `yield` inside the function, put `yield return` at the end of it.
