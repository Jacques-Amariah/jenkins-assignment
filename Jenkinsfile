
pipeline {
    agent any

    triggers {
        pollSCM('H/2 * * * *')
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo 'Checkout completed successfully'
            }
        }

        stage('Build') {
            steps {
                echo 'Build completed successfully --version2'
            }
        }

        stage('Test') {
            steps {
                echo 'Test completed successfully'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy simulation completed successfully'
            }
        }
    }
}
