pipeline {

    agent any

    stages {
        
        stage('build') {

            steps{
                echo 'building stage'
                bat 'npm run install'
                bat 'npm run build'
            }
        }
    }
}