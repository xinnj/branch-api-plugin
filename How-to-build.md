git fetch --tags https://github.com/jenkinsci/branch-api-plugin   
git rebase on tag   
mvn clean package -DskipTests "-Dplugin.version.description=tag: "