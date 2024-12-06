pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac hello.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java hello'
            }
        }
    }
}
