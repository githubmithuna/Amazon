pipeline {
    agent any

    stages {
        stage('clone code') {
            steps {
                script {
                    // Lets clone the source
                    git 'https:github.com/githubmithuna/Amazon.git';
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
