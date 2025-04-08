#{ DEVTOOLS

PROJECT_NAME=
GITHUB_ORIGIN=master

#]

#[ PROJET GLOBAL UTILITIES

# print the project init steps and requirements
project-print-init:
	@echo 1. Define the required variable in the devtools makefile
	@echo 2. Define the extra elements to ignore in the .gitignore file
	@echo 3. Fill the missing elements in the project readme
	@echo 4. Add your custom commands in the makefile
	@echo 5. Launch the 'project-init' command 

# create the project initialization branches
project-create-init-branches:
	git switch dev
	git branch dev/features/init
	git push --set-upstream origin dev/features/init
	git switch autotests
	git branch autotests/features/init
	git push --set-upstream origin autotests/features/init
	git switch design
	git branch design/features/init
	git push --set-upstream origin design/features/init
	git switch documentation
	git branch documentation/features/init
	git push --set-upstream origin documentation/features/init

# init the project
project-init:	
	@echo "Create initialization branches"
	@make project-create-init-branches
	@echo "Everything is ok"
	
#]