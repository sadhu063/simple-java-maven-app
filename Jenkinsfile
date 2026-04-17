pipeline {
    agent any
    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Complete') {
            steps {
                echo 'Job Completed!'
            }
        }
    }
}
