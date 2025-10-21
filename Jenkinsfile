pipeline {
    agent {
        node {
            label 'Agent-1'
       
    }
}
    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Test') {
            steps {
                echo 'testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploying'
            }
        }
    }
}