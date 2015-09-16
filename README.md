Cassie Cladis
CSCI 5828
Homework 2

First Edit 

Second Edit

Third Edit

Fourth Edit

Edit Merge Conflict 

Sixth Edit

Seventh Edit

Eigth Edit

Ninth Edit 

Tenth Edit

Edit Merge Conflict Part 2

Twelfth Edit

Edit Merge Conflict Part 3

Fourteenth Edit


	git init
	git add README.md
	git commit -m "Initial Commit"
	(First Edit)
	git add README.md
	git commit -m "Second Commit"
	git log ... (refer back to Initial Commit)
	git checkout ... (Initial Commit)
	git checkout -b bug-fix
	(Second Edit)
	git add README.md
	git commit -m "Third Commit"
	(Third Edit)
	git add README.md
	git commit -m "Fourth Commit"
	(Fourth Edit)
	git add README.md
	git commit -m "Fifth Commit"
	git merge master
	(Edit Merge Conflict)
	git add README.md
	git commit "Fixed Merge Conflict"
	(Sixth Edit)
	git add README.md
	git commit -m "Seventh Commit"
	git log ... (refer back fifth commit)
	git checkout "Fifth Commit"
	git checkout -b bug-fix-experimental
	(Seventh Edit)
	git add README.md
	git commit -m "Eigth Commit"
	(Eigth Edit)
	git add README.md
	git commit -m "Ninth Commit"
	(Ninth Edit)
	git add README.md
	git commit -m "Tenth Commit"
	git checkout master
	git log ... (refer back to third commit)
	git checkout "Third Commit"
	(Tenth Edit)
	git add README.md
	git commit -m "Eleventh Commit"
	git checkout bug-fix
	git log ... (refer back to seventh commit)
	git checkout "Seventh Commit"
	git merge bug-fix-experimental
	(Edit Merge Conflict Part 2)
	git add README.md
	git commit -m "Second Merge Conflict Fixed"
	(Twelfth Edit)
	git add README.md
	git commit -m "Thirteenth Commit"
	git checkout master
	git log ...(refer to eleventh commit)
	git checkout "Eleventh Commit"
	git merge bug-fix
	(Edit Merge Conflict Part 3)
	git add README.md
	git commit -m "Merge Conflict 3 fixed"
	(Fourteenth Edit)
	git add README.md
	git commit -m "Fifteenth Commit"



















