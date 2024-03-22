pipeline{
    agent{
        label "docker"
    }
    stages{
        stage("Build a code"){
            steps{
                script{
                    sh "ng build"
                }
            }
        }
    }
}