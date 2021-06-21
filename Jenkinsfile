pipeline {
    agent any 
    stages {
        stage('Code Clean') { 
            steps {
                withMaven(maven : 'maven_3_8_1'){
                    sh 'mvn clean install'
                } 
            }
        }
    }
}