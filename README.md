# agneskis.dev

Requirements:

- Git
- Docker tools

To use with the theme, you need to clone the repo with its submodules.

```bash
# Clone with submodules
git clone --recurse-submodules {repo-url}

# Clone first then initialize submodules
git clone {repo-url}
git submodule init
git submodule update
```

To start the server:

```bash
docker compose up

docker compose up --build
```

For further set up, read Hugo's [quick start guide](https://gohugo.io/getting-started/quick-start/).
