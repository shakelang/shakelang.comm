# shakelang.com

This is a fork of [shakelang.com](https://github.com/shakelang/shakelang.com/) repository (The deployment repository of [https://shakelang.com/](https://shakelang.com/))

To see actual development process, take a look at the [shakelang.com](https://github.com/shakelang/shakelang.com/) repository.

---

View deployed website at [https://shakelang.com/](https://shakelang.com/).

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ npm i
```

### Local Development

```
$ npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true npm run deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> npm run deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
