# Vite + Pocketbase on Koyeb 🚀

Pocketbase Instance runnign Vite static site for frontend inside `pb_public`, tested deployment on [Koyeb Cloud](https://app.koyeb.com)

## Client

### Vite Integrations
- Tailwind
- React
  - ShadCN UI
  - Zustand
  - swr
  - pocketbase-react


## Deployment Settings
Expose port `8090`

### Build command
```sh
pnpm build
```

### Run command
```sh
pnpm permit && pnpm dev
```

> `pnpm permit` gives permission to pocketbase CLI to be ran by the cloud instance

## Todo
- [ ] Test with `pb_public` build folder gitignored
- [ ] Landing page listing out the features & integrations
- [ ] Todo App based on the pocketbase CRUD
- [ ] Auth + OAuth with admin login
- [ ] Chat Client with Pocketbase SSE
- [ ] Gemini AI responses to the chat client
- [ ] Pocketbase Cron Job
- [ ] S3 image storage
- [ ] Backup testing
- [ ] Extended features with `pb_hooks`
- [ ] Guide on working with ignored `pb_data` folder on the Koyeb Cloud
- [ ] Video illustrating using [AnonAddy](https://addy.io) email aliases for unlimited deploys on Koyeb Cloud
