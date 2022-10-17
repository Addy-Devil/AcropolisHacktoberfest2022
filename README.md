How to contribute?
1. Fork the repository by clicking fork symbol at the top right corner.

A forked repository would be created affiliated to your account. Now open the command line on your device, add type the commands(requires git installed on your system)

2. Clone the forked repository.

   git clone https://github.com/<your-github-id>AcropolisHacktoberfest2022.git
3. Navigate to the project directory.

   cd AcropolisHacktoberfest2022
4. Create a new branch:

   git checkout -b <Add your branch name>
5. Now, in the data.json file, add your data information in below provided in json format,

{
    "github": "<your_github_user_id>"
    "firstname": "<your firstname>",
    "lastname": "<your lastname>",
    "about": "<Something about you>",
    "image": "https://github.com/<your_github_user_id>.png"
}
6. Now save your file, add it to staged area using the commond,

git add .
7. Now, your data is staged, now you can commit it to make the changes final. Use the command provided below,

git commit -m "your message"
Now deploy your changes to GitHub. Push your changes using the command git push:

git push origin -u <add-your-branch-name>
8. Submit your changes for review:

If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.

Now submit the pull request.

Soon all your changes will be merged into the master branch of this project. You will get a notification email once the changes have been merged.

Boom!!! you just got your first PR merged.
