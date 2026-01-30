pipeline {
    agent {
        label 'linux && java11'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Jenkins'
            }
        }
    }

    post {
        always {
            echo 'I will always say Hello again!'
        }
        success {
            echo 'Yay, success'
        }
        failure {
            echo 'Oh no, failure'
        }
        cleanup {
            echo 'Cleanup finished'
        }
    }
}
