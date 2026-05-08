pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/solai577/maven-gui-demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}