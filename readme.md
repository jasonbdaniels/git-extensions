# Git Extensions

Useful bash scripts that extend the functionality of git to easy to use one line commands.

## Install

1. Ensure the bash profile file exists:

	```
	touch ~/.bash_profile
	```
2. Open Profile
	
	```
	nano ~/.bash_profile
	```
	
3. Edit the profile with *Git Extension direcotry*
	
	```
	export PATH="<path>/git-extensions/scripts:$PATH"
	```
4. Update environment

	```
	source ~/.bash_profile
	```
5. Check path
	
	```
	echo $PATH
	```