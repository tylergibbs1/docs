# Mintlify Starter Kit

A starter documentation site built with [Mintlify](https://mintlify.com). Copy it, then edit the pages and `docs.json` to get your own docs deployed.

**[Follow the full quickstart guide](https://starter.mintlify.com/quickstart)**

## Quick start

```bash
npm i -g mint   # install the Mintlify CLI
mint dev        # run from the folder that contains docs.json
```

Then open `http://localhost:3000`.

## What's included

- **Guide pages**: [`index.mdx`](index.mdx), [`quickstart.mdx`](quickstart.mdx), [`development.mdx`](development.mdx)
- **Navigation and customization**: set in [`docs.json`](docs.json), with examples in [`essentials/`](essentials/)
- **API reference pages**: [`api-reference/`](api-reference/)
- **Popular components**: used throughout the pages, with reusable pieces in [`snippets/`](snippets/)

## Publishing changes

Install the GitHub app from your [Mintlify dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to connect this repo to your deployment. Changes go to production automatically after you push to the default branch.

## Troubleshooting

- **Dev server won't start**: run `mint update` to get the latest CLI.
- **A page loads as a 404**: make sure you're running in a folder with a valid `docs.json`.

See the [Mintlify documentation](https://mintlify.com/docs) for more.

## License

[MIT](LICENSE)
