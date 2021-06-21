pipeline {
    agent any
    tools {
        maven 'maven_3.8.1'
    } 
    stages {
        stage('Code Clean') { 
            steps {
                sh 'mvn clean install'
            }
        }
    }
}