# WebDev-RestApi

Github link: https://github.com/gabriela-vieira-pinto/WebDev-RestApi.git

1. To create a new repository I pressed the new button next to repositories and gave it a name (WebDev-ApiRest).
2. For this part I had added a .gitignore file with node as property as I was creating the repository.
3. As for this part I had to clone my git repository first, by doing the following:

	git clone https://github.com/gabriela-vieira-pinto/WebDev-RestApi.git

   Then I downloaded the REST.zip file given by you and extracted it into the just cloned project. 
   Having done that I went to that folder in the terminal and did as follows:

	git add *

   Next, I committed and pushed the files to the github repository with the following 2 lines:

	git commit -m “adding Rest zip folder content”
	git push

4. For this part I only had to use this simple line that created a branch called dev:

	git checkout -B dev

5. I have done this step on the 3rd point already, the steps are described under that point.
6. For this step, I selected the README option when I was creating the repository, right at the 
   beginning, just like I did for .gitignore.
7. For this step I had to push the previous created dev branch and set it to the origin branch:

	git push --set-upstream origin dev

8. I made sure both branches had the same content when I pushed them, which means this point was 
   already done. However, if I would not have done it, I would go to github and select the dev branch. 
   Then I would go to the pull requests section and press the crate a pill request tab, so that I 
   would have the option to compare the two branches and finally merge their contents.
