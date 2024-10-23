# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/main/packages/create-svelte).

## Set env vars

Set your turso or sqlite env vars

```bash
# copy the example env file
cp .env.example .env

# upcate Turso creds (if using Turso)
DATABASE_URL="libsql://db-name-user.turso.io"
DATABASE_AUTH_TOKEN="your-db-token"

# push the schema/changes to the db
npm run db:push
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://svelte.dev/docs/kit/adapters) for your target environment.
