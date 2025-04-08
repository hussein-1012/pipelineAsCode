pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build Completed.'
                timeout(time: 0, unit: 'SECONDS') {
                    sh 'sleep 2'
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Completed.'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment Completed.'
            }
        }
    }
}
