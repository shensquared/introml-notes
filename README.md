# 6.390 IntroML Lecture Notes

Source code for https://introml.mit.edu/notes

## typos and fixes:
- Edit the `markdown` files under `notes` folder
- Each note page should also have an "Edit the Page" hyperlink directly pointing to the source `*.md` file.
- Issue reports welcome

### Installation-free Edit:
Use [Sandbox](https://codesandbox.io/p/github/shensquared/introml-notes/main) for an installation-free playground, and start editing in the browser.

### Local Installation/Development:

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

Built using [Docusaurus](https://docusaurus.io/).