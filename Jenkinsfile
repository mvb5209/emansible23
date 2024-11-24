pipeline{
    agent any

    stages{
        stage('zip the file'){
            steps{
                sh 'zip ansible-${BUILD_ID}.zip * --exclude jenkinsfile'
                sh 'ls -l'
            }
        }
    }
}