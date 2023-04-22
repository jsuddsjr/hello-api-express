# hello-api-express

## How I created this service

1. Installed Node. I normally do this with `nvm for Windows`, which you can install via `WinGet` or by downloading the .MSI file from GitHub.
2. Installed the Express Generator globally.

   `npm install -g express-generator`

3. Created the new express project from standard template.

   `express hello-api`

4. Opened the project with Visual Studio Code.

   `code hello-api`

5. Installed dependencies.

   `npm install`

6. Started the express server locally.

   `npm start`

7. Updated the `users` route to return a name (routes/users.js).

   `res.send('Russel M. Nelson');`

8. Added a link to the index page (views/index.jade).

   `a(href="/users") Click here to see the users`

9. Initialized the git repository.

   `git init`

10. Added a `.gitignore` file to ignore `node_modules` folder.

    `node_modules`

11. Pushed to the remote repository on github.

    ```cmd
    git add *
    git commit -m "Initial commit"
    git remote add origin [git-url]
    git push --set-upstream origin HEAD
    ```

12. Set up an account on Render and linked my GitHub account.

13. Created a new Web App on [Render](https://render.com/) and generated the service from my github repo.

14. Tested the app. It works!

## Useful links

- [Video Demo](https://youtu.be/rGh7S3hEFng)