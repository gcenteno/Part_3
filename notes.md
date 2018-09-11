# Notes
## Part 2

1. [ ] Install [git](https://git-scm.com/downloads)
	1. Create a [github account](https://github.com/) if not existing
	2. Create repository in your account, and name it Part_2
2. [ ] Clone repository in your local files
	1. This will create directory in explorer: Part_2
3. [ ] Open Git bash
![Open Git bash](/guibash_ss.png)
![Console Git bash](/console_ss.png)

	1. git config --global user.email "you@example.com"  //Omit global if setup is only for this repository
  		git config --global user.name "Your Name"
4. [ ] execute >>
```
git init command
```
5. [ ] Create text file (preferably in [atom](https://atom.io/), notepad adds .txt extension)> name it A1.md
6. [ ] execute >> git status > to see the changes
7. [ ] execute >> git add A1.md
8. [ ] execute >> git commit -m "Initial commit"
9. [ ] git checkout -b "part-1-content"
10. [ ] Fill up the file with the info of part 1 document (just text and titles)
11. [ ] execute >> git commit -m "Add Part 1 text to Markdown doc"
	1. You can see the preview in [Dillinger: markdown preview](https://dillinger.io/).
	2. [Github help with Markdown](https://help.github.com/articles/basic-writing-and-formatting-syntax/#links)
12. [ ] execute >> git push --set-upstream origin part-1-content
13. [ ] execute >> git checkout master
14. [ ] execute >> git merge part-1-content


-------------------------
