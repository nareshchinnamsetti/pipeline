pipeline {
    agent any

    stages {
        stage('setup') {
            steps {
                sh "mkdir -p deploy"
            }
        stage('nextStage') {
            steps {
                sh "touch jenk"
            }
        }
        stage('anotherStage') {
            steps {
                echo "repeat for all your shell steps"
            }
        }
    }
}
