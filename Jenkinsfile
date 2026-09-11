pipeline {
    agent any
    stages {
        stage('Build Application') {
             steps{
                build job: 'build-web-app'
            }
        }
        stage('Deploy Application'){
            steps{
                build job: 'deploy-app'
            }            
        
        
        }
    }
}
