Steps to create a branch and merge

1. mkdir new-project
2. cd new-project
3. git clone https://github.com/olegign82/code.git
4. vi README.md (add text)
5. git add README.md
6. git status
5. git commit -m "init"
6. git checkout -b development
7. vi README.md (add more text)
8. git add README.me
9. git commit -m "More steps added to readme"
10. git switch main
11. git merge development
12. git status
13. git branch -D development
14. git push https://github.com/olegign82/code.git
