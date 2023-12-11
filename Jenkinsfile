pipeline {
agent any
stages {
stage("Build app') {
steps {
checkout scmit(branches: [[name: */main']], extensions: [], userRemoteConfigs: [[url: "https://github.com/Tejas-Pulli/Dockerize.git']])
}
}
stage("Build docker image'){
steps{
script{
bat 'docker buildt jenkins javaapp.
}
}
}
}
}
