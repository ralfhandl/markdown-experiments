# markdown-experiments

Link to [funny/name](#funny-name)

## funny/name

`markdownlint` doesn't like this section heading, despite claiming to use GFM rules:

```sh
npm run lint
```

produces

```sh
README.md:3:9 MD051/link-fragments Link fragments should be valid [Context: "[funny/name](#funny-name)"]
```

GitHub doesn't have a problem with it.
