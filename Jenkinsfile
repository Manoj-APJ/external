pipeline {
    agent any
    stages {
        stage('git hub access') {
            steps {
                url: 'https://github.com/Manoj-APJ/sample3'
            }
        }
        stage('Java code execution') {
            steps {
                script {
                    sh 'javac helloworld.java'
                    sh 'java helloworld'
                }
            }
        }
        stage('python code execution') {
            steps {
                script {
                    sh 'python helloworld.py'
                }
            }
        }
    }
}
