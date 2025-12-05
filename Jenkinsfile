pipeline {
    agent {
        label 'AGENT-1'
    }
    stages {
        stage ('scan'){
            steps {
                script {
                    echo 'building'
                }
            }
        }
        stage ('build'){
            steps {
                echo 'building'
            }
        }
        stage('testing') {
            steps {
                echo 'tesing'
            }
        }
        stage('deploying') {
            steps {
                echo 'deploying'
            }
        }

    }
}