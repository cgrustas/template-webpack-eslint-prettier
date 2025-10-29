# Template Repository - JavaScript, Webpack, ESLint, Prettier

Created to build projects for [The Odin Project](https://www.theodinproject.com/).

## Setup

1. Update the project metadata in package.json to match your new project:
   - Update the "name" and "description" fields in `package.json`
   - Update project title in `src/template.html`
2. Run npm install.
3. Run 'npm start' to confirm everything is working.

## Deployment

1. Make a new branch to deploy from by running `git branch gh-pages`. You only need to do this the first time you deploy.
2. Make sure you have all your work committed. You can use `git status` to see if there’s anything that needs committing.
3. Run git checkout gh-pages && `git merge main --no-edit` to change branch and sync your changes from main so that you’re ready to deploy.
4. Bundle your application into dist with your build command. Use `npm run build`.
5. Run each of these commands in order:
   - `git add dist -f && git commit -m "Deployment commit"`
   - `npm run deploy`
   - `git checkout main`
6. Change the source branch for GitHub Pages to `gh-pages`.
