pipeline {
    agent any
    stages {
        stage('Build') {
            when {
                changeRequest title:"when-pr"
            }
            steps {
                echo "hello World Changerequest"
            }
        }
    }
}

