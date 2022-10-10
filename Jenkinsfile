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
                echo 'Scanning done'
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
        Success { 
            echo 'Congratulations'
        }
        Failure {
            echo 'Failed'
        }
        Always {
            echo 'Go again'
        }
    }
}

