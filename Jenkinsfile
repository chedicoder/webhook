pipeline {
    agent any
    stages {
     stage('Clone & Switch to project branch') {
            steps {
                script {
                    checkout scm
                }
            }
        }
     
     stage('Test Project') {
            steps {
                sh 'cat hello'
             
            }
        }
      }
    }
