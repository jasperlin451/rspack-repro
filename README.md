# rspack-repro
A GitHub template for create reproduction with Rspack fastly.

## versions

```
    "@rspack/cli": "0.1.7",
    "webpack-cli": "^5.0.1",
    "webpack": "^5.79.0",
```

## Usages

`pnpm run build` would both run Webpack and Rspack with config `./config.mjs`

- Webpack will emits output in `./webpack-dist`
- Rspack will emits output in `./rspack-dist`