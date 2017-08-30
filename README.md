# hello-world
create to know how github work

Day-1(29-Aug-2017):

=>mistakely not checked the "initailize this repository with a README".
  -this will let you immediately clone the repository to your computer.skip this if you're import from existing repository.
=>Then, it redirect to another page(step).
=>There it is mentioned that we recommend every repository include a README,LICENSE, and gitignore.
=>After knowing that I go back to "check the README" but it shows the repository name altready exist.
=>Then,click on the README hyperLink it navigate me to the code edit page(here)

Day-2(30-Aug-2017):

=>yesterday I don't know to save the "Hello-World/README.md.
=>today I find that after edit complete switch to "preview changes" which is on top right corner of edit window(beside EDIT_FILE).
=>In that scroll down to click on "Commit new changes".
=>After that it redirect to Hello-World(My current repository).

--To create a new branch(to create a copy-content of the file which is created already in another branch to update it without affecting the existing file in that branch but both branch uses the same file only (Say README)).

=>Default branch for our current repository is MASTER and ribbon tag shows "commit-1 && branch-1 && release-0 && contributor-1".
=>Then,below the ribbon tag there is "branch:master DROPDOWN" click on it and type the new branch name and click "create new branch" or hit ENTER.path looks like <<branch:current branch(master)/current respository(toViewNextPageWithREADME)>>.
=>Then, to edit on new created branch(say README-edit) click on README.md(hyperLink) then it redirect to content page of new branch (say README-edit).path looks like <<branch:current branch(master)/current respository(toViewNextPageWithREADME)/current file(README.md)>>.
=>Now, click on pencil icon on the top left corner between desktop and delete icon which beside "Raw && Blame && History" then it redirect to the edit window(like this).path looks like <<current respository(toViewNextPageWithREADME)/current file(README.md)>>.
After edit the file switch on "preview changes" and again click on "commit new changes"(preview page).task complete

--To add description to "edit change" and to save it directly to new branch and default:master.

=> In this path <<current respository(toViewNextPageWithREADME)/current file(README.md)>>.
=> scroll down there will another edit window "commit changes" in that type description and click on save to new branch then you can type the new branch name and then click on "propose file change".
=>If I wish to commit on default branch(master) after description click on commit directly to default click on "commit changes".
=>After click on save changes it redirect to "open a pull request" in that it compare the default branch(master) file(README) with new branch(Arun@gap-newbranch-1) file README and shows changes like add line in "green" and delete in "red".

--To create a pull request(to merge the updated code to the existing code in the same branch) in own repository(toViewNextPageWithREADME)

=>In the edit window of file click on "pull request"which is on ribbon tag then it resdirect to the pull request edit window.
=>While practicing "save to new branch and default"(previous step) fortunately it redirect to the "pull request" by add the description in "commit window "commit description and save it to new branch".
=>After add the suggestion to the "commit change description" click on "create a pull request". then it redirect to the next page with the header(what I typed in the "commit change" window first box).
=>In the redirected page it shows the suggestion typed my me  in "open a pull request" and scroll down it has the original commit change description(typed while previous step).
=>Below the orginal commit change there is the merge option to the default branch, there are three opt.
=>last there is "setup continous integration to automatically test your code".(not explored). 
--create a merge commit
=>the comment add for the pull request is view-able by click on the branches(ribbon tag)then it redirect to branches page there the merged branch have a merged button click on it, it redirect to the comment of that merge.comment inside "code tag" are highligthened by background colour, "quote" are simple sentence without background colour, and "url" are shown inside open/close bracket.
--squash and merge
=>click on new pull request.
=>choose the "base" and "compare" branch from DROPDOWN button.then if there is any difference for selected "base" and "compare" only you are allowed to create pull request.
=>previously I have create pull request for base(master) and compare(Arun2Gap-newbranch-1) therefore it not again allow for pull request.
=>edit the file in the existing new branch(Arun2Gap-newbranch-1).
=>after edit it and saved 2 commit to check how the squash save 1 commit.Now the page shows the how many "commit" value added and "file changed" value.
=>the difference b/w base and compare is highlighted.then click on "create pull request".then it open the comment window I comment by heading ,bold, and italic style.
=>then choose the merge opt as squash and merge.
=>now able to see 2 commit in default(branch).then the difference is that the the commit name is not splited e.g:merge pull request %% branch name it shows like e.g:branchname(comment main heading which entered in the first box of commit change) alone.
=>another difference is that the commit is displayed in both base and compare branch. 
--rebase and merge
=>edit the file in the existing new branch(master) by mistake.
=>after edit it and saved 2 commit to check how the squash save 1 commit.Now the page shows the how many "commit" value added and "file changed" value.and also shows can't merge automatically
=>base(Arun2Gap-newbranch-1) and compare (master).
=>the difference b/w base and compare is highlighted.then click on "create pull request".then it open the comment window I comment by 
numbering list,check box list, and hype number list.
=>shows conflict to pull from default(master) to existing branch(Arun2Gap-newbranch-1).hence closed the pull request.
=>edit the file in master and save commit as "mistakely type"(commit comment should be less tha 50 in the first box).
=>repeat the same process in the squash merge and in comment by numbering(ordered) list,check box list, and  unordered list.
=>again error can't automatically merge.
=>'**note:**1.while edit the file of the branch, then check branch should be selected instead of tree.
2.**can't automatically merge** the changes done by one (typed "add a line") can't be add same change again by another one (typed "add a line") to the same file belongs to any branch but error persist due to the commit with same content is not removed from tree. but removed from branch.
3.**remove commit from tree** :need to install the "git for windows" and followed by many steps important is I choosed the "git blash" as terminal to avoid change file path.chennaiAcademy allowed to install a application without admin credentials
3.1 downloaded the project as "zip file opt" to use the terminal(Git GUI) to remove the old commit
3.2 download successful and open "git blash" use the git command line **$ git clone url(https://github.com/userName/repository)**
3.3 cloning not done throw error "unable to connect port 443" I think the office firewall block it.
3.4 tried with "git config" to loopback(my PC as github.com host)ip and tried to clone it again throws a error that **unable to connect to loopback ip and port (8080 menioned by me )**
3.5 rollback the 3.4 to **git config http.proxy github:80** and tried the cloning solved'
=>
