pipeline{
    agent{
        label "docker"
    }
    stages{
        stage("Build a code"){
            steps{
                nodejs(nodeJSInstallationName: 'NodeJs 18.13.0') {
                 sh "npm install"
                }
            }
        }
        stage("run a code"){
            steps{
                nodejs(nodeJSInstallationName: 'NodeJs 18.13.0') {
                 sh "npm run build"
                }
            }
        }
    }
}