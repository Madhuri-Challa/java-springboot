pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'build'
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
        stage('Sonar Qube') {
            steps {
                echo 'done'
            }
        }
        stage('Devlopment') {
            steps {
                echo 'Development'
            }
        }
        stage('QA') {
            steps {
                echo 'RUN UAT'
            }
        }
        stage('Staging') {
            steps {
                echo 'Staged'
            }
        }
        stage('Production') {
            steps {
                echo 'Success'
            }
        }
    }
    post { 
        success { 
            echo 'Congratulations'
        }
        failure {
            echo 'Failed'
        }
        always {
            echo 'Go again'
        }
    }
}

