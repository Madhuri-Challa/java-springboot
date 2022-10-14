pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'build'
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
                sh 'mvn test'
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
    }
}

