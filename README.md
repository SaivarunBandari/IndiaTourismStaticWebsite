# IndiaTourismStaticWebsite
## Procedure to build the project:
**Building project through Heroku and GitHub:**
1. On GitHub, create a Repository. Commit and push all the project files to the respective repository.
1. Next, click on `Create new file` , add a file named "composer.json" having content as `{}` and commit the changes with appropriate message.
2. Again click on `Create new file`, add another file named "index.php" having content as `<?php include_once("default.html"); ?>` and commit the changes with meaningful message.
3. As Heroku do not host static websites with HTML, CSS, and JS. A small little trick to get Heroku to recognize the files of our static website is to trick it into being a PHP app. This is done by adding above two files.
4. On Heroku, navigate to main page and click on `new` dropdown which is there to top right od page.
5. Select `Create New App`, enter `App Name`, choose your `Region`, and click on `Create App`.
6. Navigate to `Deploy`, and under `Deployement method` connect to your `GitHub account`.
7. There will be an text-box to enter the `repository-name` which you are willing to build using Heroku.
8. After selecting the repository, choose the master branch to deploy and click on `Deploy Branch`.
9. At this point, build will be executed and there will be a "Build succeeded" message under `Activity`.
10. Now, to open the project directly through web which has been deployed by using Heroku, click on `Open App` button which is there to the top-right corner of Heroku dashboard. Alternatively, open the following URL [https://india-tourism-static-website.herokuapp.com/](https://india-tourism-static-website.herokuapp.com/) in web browser.
11. This will right away open the deployed website.
---
