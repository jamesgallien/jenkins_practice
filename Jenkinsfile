pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'python3 --version'
            }
        }
        stage('sanity check') {
            steps {
                input 'Does everything look alright?'
            }
        }
    }
    post {
        always {
            echo 'I have finished.'
        }
    }
}