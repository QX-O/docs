# Authority-Bible-XOQ

Authority-Bible-XOQ is a spiritual teaching and documentation site for growing in biblical understanding, exploring biblical artifacts, and learning about God, the Old and New Testament, and most of all Jesus Christ.

The site is designed as a place to showcase teaching materials so others can follow, review, and gain their own understanding of Scripture and faith.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command:

```bash
npm i -g mintlify
```

Run the following command at the root of the documentation, where `docs.json` is located:

```bash
mintlify dev
```

## Publishing changes

Install the GitHub App for the deployment target to automatically publish changes after updates are pushed to the default branch.

## Troubleshooting

- If Mintlify dev is not running, run `mintlify install` to reinstall dependencies.
- If a page loads as a 404, make sure you are running the command in the folder that contains `docs.json`.
