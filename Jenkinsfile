pipeline {
    agent {
        label "AGENT-1"
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo this is build'
            }
            
        }

        stage('Test') {
            steps {
                sh 'echo this is Test'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo this is deploy'
            }
        }
    }
}