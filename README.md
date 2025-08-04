<!-- hide -->
# Making a website as a team (Git collaboration)
<!-- endhide -->
Practice your skills in Git while developing a typical website.
Each student works on a different file, for a different part of the website, and the most senior can work as Team Leader (for integration and deployment), unless the teacher prefers to be the team leader of the whole class. The Html-Template-Engine library will take care of putting all the pieces together.
## 📝 Instructions
1. The Team Leader should fork this repository on github.com and [invite other collaborators to the repo](https://github.com/breatheco-de/exercise-git-collabration/blob/master/iOBmU5zYqA.gif). Give access to the other team members on the newly forked GitHub repository, and make sure they are cloning from this new repository, not the original!
2. We are going to be building [this design](https://raw.githubusercontent.com/breatheco-de/exercise-collaborative-html-website/master/website/designs/thumb.jpg), and [this is how you can split it with the students](https://github.com/breatheco-de/exercise-collaborative-html-website/blob/master/website/designs/guide.jpg?raw=true).
3. Each contributor will have to clone the new forked repository and develop a part of the website that is coordinated with the group; each project is divided in pieces inside the `website/templates/` directory. Once everyone has their editor open, run the project in the terminal with this command:
```bash
$ npx http-server --yes -c-1
