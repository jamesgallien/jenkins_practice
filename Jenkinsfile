pipeline {
    agent any
//     agent {
//         docker {
//             image 'python:3.5.1'
//         }
//     }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'python3 --version'
            }
        }
    }
    post {
        always {
            echo 'I have finished.'
        }
    }
}