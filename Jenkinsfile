pipeline {
    agent any 
    stages {
        stage("Build") {
            steps {
                echo 'Hello, Maven'
                sh 'df -kh'
            }
        }
        stage("Test") {
            steps {
                echo 'Hello, JDK'
                sh 'java --version'
            }
        }
    }
}
