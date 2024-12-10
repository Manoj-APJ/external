pipeline {
    agent any
    stages {
        stage('git hub access') {
            steps {
                git url: 'https://github.com/Manoj-APJ/sample3'
            }
        }
        stage('Java code execution') {
            steps {
                script {
                    sh 'javac Helloworld.java'
                    sh 'java Helloworld'
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
