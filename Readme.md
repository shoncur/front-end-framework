# Basic Framework For Front End Vanilla.js Projects

## Preflight Check
1. Run npm install from the framework root folder. This will create the node_modules and install the dependancies found in the package.json file.
```bash
  npm install
```

1. Run development build using the parcel bundler.
```bash
   npx parcel src/index.html
```
or
```
  npm start
```

1. Run production build using the parcel bundler.
```bash
   npx parcel build src/index.html
```
or
```
  npm run build
```

## GIT SETUP
1. .gitignore ignores files and they will not be uploaded to remote repository.

1. Set up repo from VS Code
2. User Profile Icon
3. Sign in to sync settings
4. Sign in with github
5. Click the green button to accept
6. Click on the Source Control Tab
7. Publish to git select public repo
8. Publish the folder to the github repo

## Remove Repo
1. Go to the Github repo
2. Select settings
3. Scroll to the bottom
4. Delete the repo

## If You Make An Init Mistake
search your local repository for hidden files.
```bash
  ls -lah
```

looking for a file that says
```
  .git
```

looking for a file that says
```
  rm -rf .git
```

Then re-init your repository

# Deploying To Netlify
1. Account at netlify log in
2. Click on team name select sites tab
3. Site click on the deploy from git
4. Select GitHub
5. Show your repo's
6. Select the repo to build
7. Make sure to write the correct build command
```
  parcel build src/index.html
```
1. Netlify will deploy the repo.

# VS CODE
1. Make changes
2. Commit the changes
3. Push the changes to remote repo.
4. Netlify see's changes and build a new site