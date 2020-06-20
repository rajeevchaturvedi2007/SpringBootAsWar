# SpringBootAsWar
### This project created using the Spring Boot without Tomcat and deploy in the AWS EC2 instance of Tomcat in the cloud. 
### Tomcat is runing on the EC2.
### To deploy the WAR file, Open the Tomcat Management Console and then using theTomcat GUI, upload the WAR file and deploy it. 

## Do not run from command prompt (No Spring Boot main() method class), it is using Servlet to make it deployable in external AWS - EC2 -Tomcat

### The end point URL show the EC2-Tomcat URL (Not local) after deploying in the external EC2 Tomcat 

## End Point: http://ec2-3-9-23-72.eu-west-2.compute.amazonaws.com:8080/springBootWar/

## This project has no any database or databse interaction.

### Key Git Commands:

 -------------- Git Commands -------------------------------

# 1. git clone cloneURL
# 2. git add –all
# 3. git commit -m “Initial Message"
# 4. git push -u origin master
# 5. git status

# Move from one Branch (feature) to master or vice versa
## git fetch && git checkout branchName
### 	Example: git checkout master  ( Suppose you are in feature branch currently and want to move in master

# Merge branches:
## a.	git merge master feature_1234 ( merging feature with master)
## b.	git push -u origin master  

