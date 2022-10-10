pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Build Completed'
            }

        }
        stage('test') {
            steps {
                echo 'Tesing Done'
            }

        }
        stage('sonar qube') {
            steps {
                    echo 'Scanning Done'
            }

        }
        stage('Development') {
            steps {
                    echo 'Development Done'
            }
        }   
        stage('QA') {
            steps {
                echo 'UAT Environment'
            }
        }
        stage('Staging') {
            steps {
                echo 'Staging'
            }
        }
        stage('Production') {
            steps {
                echo 'Production Completed'
            }
        }

    }

    
}

post {
    failure {
        echo 'Failed'
    }
    Success {
        echo 'Congratulations'
    }
}