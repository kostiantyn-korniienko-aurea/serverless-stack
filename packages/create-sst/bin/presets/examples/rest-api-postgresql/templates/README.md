# How to use PostgreSQL in your serverless app

An example serverless app created with SST.

## Getting Started

[**Read the tutorial**](https://sst.dev/examples/how-to-use-postgresql-in-your-serverless-app.html)

Install the example.

```bash
$ npm init serverless-stack --example rest-api-postgresql
# Or with Yarn
$ yarn create serverless-stack --example rest-api-postgresql
```

## Commands

### `npm run start`

Starts the Live Lambda Development environment.

### `npm run build`

Build your app and synthesize your stacks.

### `npm run deploy [stack]`

Deploy all your stacks to AWS. Or optionally deploy, a specific stack.

### `npm run remove [stack]`

Remove all your stacks and all of their resources from AWS. Or optionally removes, a specific stack.

### `npm run test`

Runs your tests using Jest. Takes all the [Jest CLI options](https://jestjs.io/docs/en/cli).

## Documentation

Learn more about the SST.

- [Docs](https://docs.sst.dev/)
- [@serverless-stack/cli](https://docs.sst.dev/packages/cli)
- [@serverless-stack/resources](https://docs.sst.dev/packages/resources)
