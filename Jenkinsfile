pipeline {
    agent any 
    stages {
        stage("Build") {
            steps {
                echo 'Hello, Maven'
                sh 'mvn --version'
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
