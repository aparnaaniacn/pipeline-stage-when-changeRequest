pipeline {
    agent any
    stages {
        stage('Build') {
            when {
                changeRequest()
            }
            steps {
                echo "hello World Changerequest"
            }
        }
    }
}

