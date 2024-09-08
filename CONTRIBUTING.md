# Contribute to the OpenAPI Overlays Specification

We welcome contributions and discussion.
Bug reports and feature requests are welcome, please add an issue explaining your use case.
Pull requests are also welcome, but it is recommended to create an issue first, to allow discussion.

Questions and comments are also welcome - use the GitHub Discussions feature.
You will also find notes from past meetings in the Discussion tab.

## Build the HTML version to publish

We use ReSpec to render the markdown specification as HTML for publishing and easier reading.
These instructions explain how you can build the HTML locally.

You will need NodeJS 18 or later.

Install dependencies:

```sh
npm install
```

Produce stand-alone HTML files in the local `deploy/overlay` folder:

```sh
npm run build
```

Note that Linux users may need to add `--no-sandbox` to run `npx respec` as found in the `scripts/md2html/build.sh` file.