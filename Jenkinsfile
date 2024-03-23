pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                // Execute build steps here
                echo 'Building the application...'
            }
        }
        stage('test') {
            steps {
                // Execute test steps here
                echo 'Testing the application...'
            }
        }
        stage('deploy') {
            steps {
                // Execute deployment steps here
                echo 'Deploying the application...'
            }
        }
    }
    post {
        success {
            // Actions to be performed if the pipeline succeeds
            echo 'Pipeline succeeded!'
        }
        failure {
            // Actions to be performed if the pipeline fails
            echo 'Pipeline failed!'
        }
    }
}
