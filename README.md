# Know Your AI Docs

This folder contains the Mintlify documentation site for **Know Your AI**.
It covers the product overview, core concepts, evaluation workflows, and monitoring guidance.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the docs locally. To install, run:

```
npm i -g mint
```

Run the following command at the root of the docs (where `docs.json` lives):

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Push updates to the `beta` branch (or your default docs branch) to publish changes through your existing deployment pipeline.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
