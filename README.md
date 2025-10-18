# Link to the demo
accessible here: [https://aviddollars.github.io/star_wars_shop/](https://aviddollars.github.io/star_wars_shop/)

## Technologies used
- Angular v19
- Tailwind v4

## Local development
Local development is done in lightweight Node-based Docker container
which has live code-reload capabilities to simplify development process.

Prerequisites for local development:
- Docker Engine installed: [https://docs.docker.com/engine/install/](https://docs.docker.com/engine/install/)

Steps to start local development:
```bash
# clone the repository:
git clone https://github.com/AvidDollars/star_wars_shop.git

cd star_wars_shop/

# start DEV container in watch mode:
docker compose watch angular-dev

# shut down DEV container
docker compose down
```

## Deployment process to GitHub Pages
```bash
# all changes to be done in the "main" branch:
git checkout main

# commit the changes before the deployment:
git add <files>
git commit -m <commit-message>

# triggers build and deployment to GitHub Pages:
./deploy_changes
```
