# lunar

maintainer: jimmy lim <mirageglobe@gmail.com>

yet another lunar calendar conversion: a lunar to solar conversion in JavaScript

# known problems

```text
# time issue
there is an issue if time is between 23:00:00 - 01:00:00, it time of rat which means day +1
```

# to use

```bash
# run with node
node lunar.js

# test with ava
npx ava

# ava test with watch (test only changed files)
npx ava --watch
```

# to do

- [] test <https://github.com/cucumber/cucumber-js> vs <https://github.com/avajs/ava>

# references

- <https://github.com/gopherjs/gopherjs>
