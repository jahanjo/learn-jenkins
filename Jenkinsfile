pipeline {
    agent {
        label 'ansible'
    }
    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello world!'
            }
        }
    }
    post {
        always {
            echo "Send an email"
        }
    }
}