
############   GIT ################3


git remote add origin https://github.com/{yourGitHubUsername}/maven-project.git
	git remote add origin https://github.com/AshishKumar-Espire/UIA_RELEASE1.0_BRANCH.git
	
git status
		: It shows Untracked files
		
git add –A

git commit -m "Initial commit"

git push origin master

git add –A && git commit -m "Format change"





	
	################## MAVEN ###################3
	
	# maven-project
This is my Maven project from MuleSoft's development class
## How to run the project
1. Add the remote repository: 'git remote add origin'
https://github.com/{yourGitHubUsername}/maven-project.git`
2. Enter the repo: 'cd maven-project'
3. (Optional) Set your MULE_HOME env variable: 'export'
MULE_HOME={locationOfMuleInstall}`
4. Package and deploy: 'mvn install'

E:\UnxUtils\usr\local\wbin\date.exe > E:\UIAMuleSVNRepo\svn.currentVersion.txt
E:
cd E:\UIAMuleSVNRepo\uia
svn --username uia.esb --password India@4321 update >> ..\svn.currentVersion.txt
call mvn clean package -DskipMunitTests
cd E:\Server\mule-enterprise-standalone-3.8.5\apps
RMDIR "uia-1.0.0-SNAPSHOT" /S /Q
copy E:\UIAMuleSVNRepo\uia\target\uia*.zip E:\Server\mule-enterprise-standalone-3.8.5\apps
E:\Server\mule-enterprise-standalone-3.8.5\bin\mule.bat

