git-diff - Show changes between commits, commit and working tree, etc..
Let's take an example: I created a Git repository which is "difftest".
No, it's not a formal repo, but it's quite serious .
Then I created "b" and "a".
Include a text in "a" and "b" like this:
in file "b":
hello I'm Mohamed and that's a diff test for me
man city and real madrid
in file "a":
hello I'm Mohamed and that's a diff test for me
man city vs Barecelona.
the followinf comman is to include "a" and "b" in a diff file called ""
diff a b > sw.diff
After  display the file sw.diff with cat command:
cat sw.diff
it will sho u this:

< hello I'm Mohamed and that's a diff test
< man city vs barça
\ No newline at end of file
---
> hello I'm Mohamed and that's a diff test for me
> man city and real madrid
\ No newline at end of file

 For more visit: https://www.freecodecamp.org/news/git-diff-command/
