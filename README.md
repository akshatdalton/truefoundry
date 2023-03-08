# Getting-Started
- Clone the repo: `git clone https://github.com/akshatdalton/truefoundry.git`.
- Create a [GitHub OAuth app](https://docs.github.com/en/developers/apps/building-oauth-apps/creating-an-oauth-app) and set homepage url to `http://localhost:3000` and callback url to `http://localhost:3000/github/callback`.
- Check the yarn and npm versions required in the `package.json` file.
- Run `yarn install` to build the dependencies.
- Rename `.example.env` file to `.env`.
- Set `GITHUB_CLIENT_ID` and `GITHUB_CLIENT_SECRET` values from the GitHub OAuth app created (you first need to generate a client secret) and `GITHUB_SCOPES` to `repo`.
- Run `yarn start` to start the server.

# How to use
- Go to `http://localhost:3000` or `https://truefoundry.herokuapp.com`.
- Click on `Click me to generate a repo`, authorize the app and this will create a repo with name `fastapi-app` by using the template present in `akshatdalton/fastapi-template`.

# Execution flow
You click on `Click me to generate a repo` -> It takes you to the authorization page -> Repo with sample files are created.

