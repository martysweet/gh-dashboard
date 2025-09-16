# gh-issue-dashboard
Simple HTML dashboard to collate multiple Github Project boards.

This can be useful if you keep track of tasks across multiple Github Projects, and what an overview of all tasks in one place.

## Deployment
Deploy the index.html file to a place of your choosing (e.g. GitHub Pages, Netlify, Vercel, etc.)

## Usage
- Uses GitHub OAuth App with Device Flow to authenticate (https://github.com/settings/developers)
- Device flow allows authentication without a redirect URI, making it perfect for static deployments
- If deploying manually, change GITHUB_CLIENT_ID in index.html to your own OAuth app client ID
- During authentication, you'll be given a code to enter at https://github.com/login/device
