# Notes
## Part 2

1. [ ] Install git
	1.1 Create a github account if not existing
	1.2 Create repository in your account, and name it Part_2
2. [ ] Clone repository in your local files
	2.1 This will create directory in explorer: Part_2
3. [ ] Open Git bash
	3.1 git config --global user.email "you@example.com"  //Omit global if setup is only for this repository
  		git config --global user.name "Your Name"
4. [ ] execute >> git init command
5. [ ] Create text file (preferably in atom, notepad adds .txt extension)> name it A1.md
6. [ ] execute >> git status > to see the changes
7. [ ] execute >> git add A1.md
8. [ ] execute >> git commit -m "Initial commit"
9. [ ] git checkout -b "part-1-content"
10. [ ] Fill up the file with the info of part 1 document (just text and titles)
11. [ ] execute >> git commit -m "Add Part 1 text to Markdown doc"
	11.1 You can see the preview in [markdownlivepreview](http://markdownlivepreview.com/).
12. [ ] execute >> git push --set-upstream origin part-1-content
13. [ ] execute >> git checkout master
14. [ ] execute >> git merge part-1-content


-------------------------
Markdown preview:


echo "# Part_3" >> README.md
git init
git add README.md
git commit -m "first commit"

git push -u origin master
