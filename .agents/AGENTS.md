# Workspace Style Rules

- **Authentication Reminders**: At the start of a session or task, proactively remind the user to authorize/log into Cloudflare (via `npx wrangler login`) and Git if they aren't already authenticated. This allows the agent to handle all Git pushes and Cloudflare deployments autonomously so the user doesn't have to do it manually.
