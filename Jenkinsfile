pipeline {
    agent {
        label 'AGENT-1'
    }
    agent any
    
    stages {
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