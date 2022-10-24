# GIT COURSE

### description du projet git course

Using a simple * wildcard works fine, if you in the same directory as the files you want to add:

qsdqsd
git add *.c
If you are in a different subdirectory of your repository, then you could use a pathspec with a magic signature, as described in the git glossary, to add all files with .c extension in any directory in your working tree:

git add :/*.c
Any git pathspec starting with : has special meaning. In the short form, the leading colon : is followed by zero or more "magic signature" letters. The magic signature / makes the pattern match from the root of the working tree, even when you are running the command from inside a subdirectory.
oiqjsdpqls;d