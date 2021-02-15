pipeline {
    agent any

    tools {
        maven 'maven-latest'
    }

    stages {

        stage('Clean') {
            steps {
                sh 'mvn clean'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn -B package'
            }
        }
    }
}
