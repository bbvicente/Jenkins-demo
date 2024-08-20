pipeline {
    agent any

    stages{
        stage('Build'){
            steps{
                sh "echo Building Stage1"
            }
        }
        stage('Test'){
            steps{
                sh "echo Tetsing Stage2"
            }
        }
        stage('Git Webhook'){
            steps{
                sh "echo Git Webhook"
            }
        }
        stage('Deploy'){
            steps{
                sh "echo Deploying Stage3"
            }
        }
    }
}