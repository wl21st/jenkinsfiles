pipeline {
    agent any

    tools {
        maven 'maven-latest'
    }

    stages {
        stage('Build') {
            steps {
                sh 'mvn -B package'
            }
        }
    }
}
