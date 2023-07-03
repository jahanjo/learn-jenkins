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
        stage('Stage 2') {
                    steps {
                        echo 'Hello world again!'
                        mail bcc: '', body: 'Hello...How are you', cc: '', from: '', replyTo: '', subject: 'Intro', to: 'jahangeer439@gmail.com'
                    }
        }
    }
    post {
        always {
            echo "Send an email"
        }
    }
}