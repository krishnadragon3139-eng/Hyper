# Welcome to your Lovable project

## Project info

**URL**: https://lovable.dev/projects/4b4b5338-c581-41de-bbc9-1bd116394c9d

## How can I edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/4b4b5338-c581-41de-bbc9-1bd116394c9d) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the app in your browser with all React components loaded.
npm start
```

Do not open `index.html` directly from File Explorer. This project uses Vite to compile TypeScript/React and load its component imports. `npm start` runs the required local server and opens the app.

## Configure Groq

Create a Groq API key and replace `PASTE_YOUR_GROQ_API_KEY_HERE` in `src/lib/groq-service.ts` for local testing. This frontend sends requests directly to Groq, so the key is included in browser code and must not be used in a deployed/public app. For production, route requests through a server-side endpoint and store the key there.

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with .

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/4b4b5338-c581-41de-bbc9-1bd116394c9d) and click on Share -> Publish.

## I want to use a custom domain - is that possible?

We don't support custom domains (yet). If you want to deploy your project under your own domain then we recommend using Netlify. Visit our docs for more details: [Custom domains](https://docs.lovable.dev/tips-tricks/custom-domain/)
