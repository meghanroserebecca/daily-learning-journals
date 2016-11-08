<p>Branching! 'Origin' is your default main remote, and 'master' is your default main branch of your repository.<br />
Basic git Workflow: modify, add, commit.<br />
Imagine your repo is code for a vital website.<br />
Further imagine that your production server is running using code on the master branch.<br />
We don't want changes made willy-nilly to that master branch. We only want tested, vetted code to end up in master<br />.
So we ask dev teams to implement fixes & features on branches.</p>

<p>ALWAYS branch off of MASTER!!!</p>

<p>Git command: checkout<br />
It has 2 uses: the first takes a branch name as an argument and moves you to that branch (timeline)<br />
git checkout [branch name] takes you to another (preexisting) branch. <br />
git checkout -b [new branch name] both creates and moves you to a new branch. <br />
</p>

<p>Pushing Different branches<br />
In order to push this new branch to GitHub we need to clarify in the push command that we are pushing origin [name of new branch]</p>

<p>Pull Requests allow us to work together all over the world.</p>
