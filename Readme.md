# JaLuLe Website

Built using [Zola](https://www.getzola.org/). This used to be a Laravel project but I got bored of that. It's all static anyway so I might as well try something new.

## Building

```bash
yarn install --frozen-lockfile
zola build
```

To deploy just copy the contents of the generated `public/` directory to any static host.
