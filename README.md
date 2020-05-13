# Docker for SilverStripe 4 #

Docker image based on Debian Stretch (PHP 7.2) configured for Silverstripe CMS 4 development.

Based on twohill/docker-silverstripe4 (just using date.timezone = Europe/Berlin")

Merge the original (update this repo):

Clone it locally
git clone https://github.com/lhasselb/docker-silverstripe4.git

Open Terminal.
Change the current working directory to your local project.
Check out the branch you wish to merge to. Usually, you will merge into master.

$ git checkout master

Pull the desired branch from the upstream repository. This method will retain the commit history without modification.

$ git pull https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git master

If there are conflicts, resolve them. For more information, see "Addressing merge conflicts".
Commit the merge.
Review the changes and ensure they are satisfactory.
Push the merge to your GitHub repository.

$ git push origin master
