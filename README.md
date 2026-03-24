# Todo example using Supabase + Svelte + Vite w/ modifications for self-hosted Supabase

- Frontend:
  - Svelte, TypeScript
  - [Supabase.js](https://supabase.com/docs/library/getting-started) for user management and realtime data syncing.
- Backend:
  - Supabase, self-hosted using instructions at https://supabase.com/docs/guides/self-hosting/docker
  
### 1. Login to the self-hosted Supabase dashboard

DASHBOARD login credentials will be found in the supabase-project directory > .env file.

### 2. Run "Todo List" Quickstart

After logging into Supabase, select `SQL Editor` > `COMMUNITY` > Quickstarts and select the `Todo List` Quickstart. Run the `Todo List` Quickstart SQL to populate the database.

### 3. Get the URL and Key

Click the "Connect" button at the top of the Supabase dashboard page, open the API Keys tab, and find your Project URL and `Anon` Key; you'll need these in the next step.

### 4. Clone this repository

`git clone https://github.com/mu-jchung/coolify-svelte-todo-test.git`

### 5. Set up local dev and run

Resolve dependencies with the command

`npm i --legacy-peer-deps`

cd to coolify-svelte-todo-test and copy .env.example to .env.local. Modify .env.local to contain the URL and Anon Key from Step 3 above.

Run the app with the command

`npm run dev`

Test the app. Make sure that the sign-up email verification works correctly.
