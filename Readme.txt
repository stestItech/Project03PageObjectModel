1. Run the command below to start jenkins from the folder where jenkins jar file is located:
java -Dhudson.model.DirectoryBrowserSupport.CSP="" -jar jenkins.war
2. Open http://192.168.0.75:8080/ (localhost) to get Jenkins web application
3. Log in as admin/default password from .jenkins folder or create a new one
4. Make push to git remote repository to start maven build.