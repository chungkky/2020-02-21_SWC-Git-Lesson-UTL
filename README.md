# 2020-02-21 Software Carpentry Workshop, University of Toronto Libraries, St George campus
**Day 2, Afternoon**

### Version Control with Git 

**Instructor**  
Kathy Chung <kky.chung@utoronto.ca>, Research Associate, Records of Early English Drama, UT  

**Workshop Outline and Etherpad**  
https://uoftcarpentries.github.io/2020-02-20-utsg/  
https://pad.carpentries.org/utfeb2020


### Credits/Sources
The cartoons:
* PhD Comics "nofFinal.doc" http://phdcomics.com/comics/archive.php?comicid=1531
* xkdc "Git" https://xkcd.com/1597/
* xkdc "Git commit" https://xkcd.com/1296/  

Lesson:
* SWC Lesson: Version Control with Git https://swcarpentry.github.io/git-novice/


### Some Userful Resources
* SWC Git Lesson Cheat Sheet https://swcarpentry.github.io/git-novice/reference
* GitHub's Git Cheat Sheet https://github.github.com/training-kit/
* Visualizing Git Concepts with D3 https://onlywei.github.io/explain-git-with-d3/
* Collaborative Development Models/Workflows https://help.github.com/articles/about-collaborative-development-models/
* Mozilla Science Working Open Workshop (WOW) lesson GitHub for Collaborating on Open Projects https://mozillascience.github.io/working-open-workshop/github_for_collaboration/
* The Pro Git Book, standard reference https://git-scm.com/book/en/v2
* Atlassian has several good tutorials on Git:
  * Index of All Tutuorials https://www.atlassian.com/git/tutorials  
  * Getting Started https://www.atlassian.com/git/tutorials/setting-up-a-repository
  * Collaborating https://www.atlassian.com/git/tutorials/syncing
  * Git Workflows https://www.atlassian.com/git/tutorials/comparing-workflows
* Creative Commons site with useful explanations about types of licenses you can use with your work https://creativecommons.org/share-your-work/licensing-examples/
  
  
### Selected Git Terminology/Jargon
#### Repos and Branches

Term | Description
----- | ------------
Origin (repo) | Your remote repo (on GitHub) it is the "origin" for your local copy. Either it is a repo you created yourself or it is a fork of someone else's GitHub repo.
Upstream (repo)| The main repo (on GitHub) from which you forked your GiHub repo.
Local (repo) | The repo on your local computer.
Master | The main branch (version) of your repo.


#### Basic Commands/Actions

Term | Explanation
---| ---
Fork | Make a copy of someone else's GitHub repo in your own GitHub account.
Clone | Make a copy of the your GitHub repo on your local computer.  In CLI: 'git clone' copies a remote repo to create a local repo with a remote called `origin` automatically set up.
Pull | You incorporate changes into your repo.
Add | Adding snapshots of your changes to the "Staging"  area.
Commit | Takes the files as they are in your staging area and stores a snap shot of your files (changes) permanentaly in your Git directory.
Push | You "push" your files (changes) to the remote repo.
Merge | Incorporate changes into the branch you are on.
Pull Request | Term used in collaboration. You "issue a pull request" to the owner of the upstream repo asking them to pull your changes into their repo (accept your work).

