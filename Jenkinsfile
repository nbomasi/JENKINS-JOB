pipeline {
    agent any
    stages {
        stage("A") {
            steps {
                sh 'echo "========executing A========"'
            }
            post {
                always {
                    sh 'echo "========always========"'
                }
            }
        }
    }
}