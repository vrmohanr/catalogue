@Library('jenkins-shared-library') _

def configMap = [
    project: "roboshop",
    component: "catalogue"
]
if (env.BRANCH_NAME.equalsIgnoreCase('main')){
    echo " Main branch is not executing now"
}
else {
    nodejsEKSPipeline(configMap)
}