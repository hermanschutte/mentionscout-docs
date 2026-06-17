# MentionScout Docs

The official documentation for [MentionScout](https://mentionscout.com), the platform for tracking how your brand is mentioned and cited across AI answer engines.

The site is built with [Mintlify](https://mintlify.com). Content lives in `.mdx` files and site configuration lives in `docs.json`.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```
npm i -g mint
```

Run the following command at the root of the docs (where `docs.json` lives):

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Changes are deployed to production automatically after pushing to the default branch, via the connected Mintlify GitHub app.

## Need help?

### Troubleshooting

- If the dev environment isn't running: run `mint update` to get the latest CLI.
- If a page loads as a 404: make sure you are running in a folder with a valid `docs.json`.

### Resources

- [Mintlify documentation](https://mintlify.com/docs)
- Questions about MentionScout: [support@mentionscout.com](mailto:support@mentionscout.com)
