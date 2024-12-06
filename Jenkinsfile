pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac hello world.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java hello world'
            }
        }
    }
}
