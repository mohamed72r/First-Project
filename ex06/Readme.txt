A gitignore file specifies intentionally untracked files that Git should ignore.
If you want to ignore all files with a specific name, you need to write the literal name of the file.
For example, if you wanted to ignore any nop.exe files, you would add the following to .gitignore:
nop.exe.
To ignore an entire directory with all its contents, you need to include the name of the directory with the slash / at the end:
test/
For example if u want to ignore all files ending waith :".a" or ".exe"
You have to creat a ".gitignore" file in ur directory.
Files with a dot (.) preceding their name are hidden by default.
you have to include in your .gitignore file the type of file u want git to ignore.
Example:
/*.[oa]
/nop.exe

After you have to create a bash file which lists all the ignored files.
Touch git_ignore.sh
 Use this command to list all of the ignored files by git:

 git ls-files --others --ignored --exclude-standard
 
 REMARK:The files that you want to be ignored have to be in the same directory as the bash file.
 For more informations :https://www.freecodecamp.org/news/gitignore-file-how-to-ignore-files-and-folders-in-git/#create
