#[ DEVTOOLS

PROJECT_NAME=
GITHUB_ORIGIN=master

#]

#[ PROJET GLOBAL UTILITIES

# print the project init steps and requirements
project-print-init:
	@echo 1. Define the required variable in the devtools makefile
	@echo 2. Define the extra elements to ignore in the .gitignore file
	@echo 3. Create the linked GitHub Project
	@echo 4. Fill the missing elements in the project readme
	@echo 5. Add your custom commands in the makefile
	@echo 6. Launch the 'project-init' command
	@echi 7. Go to configure the project branches protection rules

# create the project initialization branches
project-create-init-branches:
# autotests branch
	git branch autotests
	git switch autotests
	git push --set-upstream origin autotests
	git branch autotests/features/init
	git switch autotests/features/init
	git push --set-upstream origin autotests/features/init
	git switch master
# design branch
	git branch design
	git switch design
	git push --set-upstream origin design
	git branch design/features/init
	git switch design/features/init
	git push --set-upstream origin design/features/init
	git switch master
# dev branch
	git branch dev
	git switch dev
	git push --set-upstream origin dev
	git branch dev/features/init
	git switch dev/features/init
	git push --set-upstream origin dev/features/init
	git switch master
# documentation branch
	git branch documentation
	git switch documentation
	git push --set-upstream origin documentation
	git branch documentation/features/init
	git switch documentation/features/init
	git push --set-upstream origin documentation/features/init
	git switch master

# init the project
project-init:	
	@echo "Create initialization branches"
	@make project-create-init-branches
	@echo "Everything is ok"
	
#]