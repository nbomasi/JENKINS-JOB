pipeline {
    agent{
        label "any"
    }
    stages {
        stage("A") {
            steps {
                sh 
                echo "========executing A========"
            }
            post {
                sh  echo "========always========"
                }
        }
    }
}                