# git-svn-diff

This is a shell script file for changing a git-style diff file to an svn-style diff file.
The git-svn-diff originally by http://mojodna.net/2009/02/24/my-work-git-workflow.html.

# Usage
1. modify git's ~/.gitconfig by adding content at the end of the file:
[alias]
  svn-diff =!git-svn-diff.sh

2. put the git-svn-diff in git's bin PATH; for version 2.9+, the directory would be "Git\mingw64\bin\" in Windows.
3. use "git svn-diff>sample.patch" in git bash
