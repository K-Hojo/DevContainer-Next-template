# DevContainer-Next-template
This is a template repository for Node.js projects developing in docker-in-docker Dev Container environments.

## usage
### Create your repository from this template
1. If you're reading this, you should be at https://github.com/K-Hojo/DevContainer-Node-template.
2. Click "Use this template" button in the page.
3. You'll see "Create a new repository from DevContainer-Node-template" page.
4. Enter your repository name and so on as usual.
5. New repository with the codebase of this repository committed as the initial commit will be created.
6. Clone the remote repository to your local one.

### Open your repository in Dev Container environment
1. Open it with VSCode.
2. Install "Dev Containers" plugin to your VSCode if you don't have it yet.
3. Edit devcontainer.json. For example, rename: `"name": "Existing Docker Compose (Extend)"`.
4. Press F1 key and choose "Dev Container: Reopen in Container".
5. Please wait: starting container...

### Create your Next.js app
1. Run `mkdir src && cd src`.
2. Run `docker compose build` to build the dockerfile.
3. Run `docker compose run --rm app npx create-next-app@latest .` to create next app.
4. Run `docker compose up` to start local server.
5. Go to http://localhost:3000/ (port number is 3000 by default).
6. Happy hacking!