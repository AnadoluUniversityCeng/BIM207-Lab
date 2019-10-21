

# BIM207-Lab1

## Prerequisites
- Check JDK is installed and path is set in environment variables.
	> java -version.
	if not recognized make sure JDK is installed and then set the PATH via command line:
	>set JAVA_HOME=java directory
	>set PATH=%PATH%;%JAVA_HOME%\bin

- Check Maven is installed and path is set in environment variables.
	>  mvn --version.
	if not recognized make sure Maven is installed and then set the PATH via command line:
	>set M2_HOME=maven directory
	>set PATH=%PATH%;%M2_HOME%\bin

## Assignment
- Clone your private githubclassroom repository to your working repository  
- Create a maven project by following the instructions below
[https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html)
- Add Apache Maven Shade Plugin and configure your jar file name as your GitHub username
- Push your work to the repository without target folder
- Make sure that "java -jar target\GitHubUserName.jar" command prints out "Hello  World!"
