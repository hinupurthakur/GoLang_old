The Google recommended file structure.
There are three main directories in GoLang :
1. src: It will hold all the source codes or files.
2. pkg: It will only store compiled object code that will end with .a (any compiled code files)
3. bin: After compileing .txt or .exe file it will come under bin.
If you are using Github.com to store your packages.
Then a new folder is to be created :
/src/github.com/<project_name>
e.g. /src/github.com/Trial_Project

#To install package.
	- go get <URL w/o https://>
	e.g.
	- go get https://github.com/grsmv/goweek

