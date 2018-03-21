
https://github.com/aleksandr-m/gitflow-maven-plugin

# store creadential enabling batch execution 
$ git config credential.helper store

# Without creating a release branch
$ mvn gitflow:release-start gitflow:release-finish -B 

# Without creating a release branch
$ mvn gitflow:release 
