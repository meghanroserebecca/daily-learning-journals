# LJ Code 201 - Day 14
Shorthand for our long-ass functions we wrote to ensure non-duplicating randomness of image generation in our **bus_mall** project!! <br />
<ul>function randomUniqueIndexes( ) { <br />
  var indexes = [ ]; <br />
  var uniqueIndex; <br />

  for (var i = 0; i < 3; i++) { <br />
    do { <br />
      uniqueIndex = Math.floor(Math.random() * paths.length); <br />
      } while (indexes.indexOf(uniqueIndex) !== -1 || <br />
      displayIndexes.indexOf(uniqueIndex) !== -1); <br />
<br />
      indexes.push(uniqueIndex); <br />
      } <br />
<br />
    return indexes; <br />
}</ul><br />
-->displayIndexes is a variable previously established that stores the indexes generated in the previous set of images shown (I used "previousSet" in my code)<br />
<br />

<p>(1)Fork the organization repo <br />
(2)everyone clones the Forkset remotes (a) git remote -v (b) origin is your fork (c) add the organization repo as your remote... git remote add upstream <org-url> <br /></p>

(1)Create branch <br />
(2)add, commit, push <branch_name>.  <br />
(3)pull request to org-repo -->do not merge our own pull requests <br />
(4)for others' pull requests: pull  <ul><li>(a)commit changes </li><li>(b) switch to master </li><li>(c) git pull upstream master</li><li> (d) switch back to your branch </li><li>(e) git merge master</li></ul>
