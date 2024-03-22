pipeline{
    agent{
        label "docker"
    }
    stages{
        stage("Build a code"){
            steps{
                nodejs(nodeJSInstallationName: 'NodeJs 12.22.9') {
                    sh "npm install"
            }
        }
    }
}