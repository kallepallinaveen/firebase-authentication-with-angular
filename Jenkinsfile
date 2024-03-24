pipeline{
    agent{
        label "docker"
    }
    stages{
        stage("Build a code"){
            steps{
                nodejs(nodeJSInstallationName: 'NodeJs 6.13.1') {
                 sh "npm install"
                }
            }
        }
        stage("run a code"){
            steps{
                nodejs(nodeJSInstallationName: 'NodeJs 6.13.1') {
                 sh "ng build"
                }
            }
        }
    }
}