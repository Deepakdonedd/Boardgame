pipeline {
    agent any
     
    tools {
        maven 'maven3.9'
        jdk 'jdk17' 
    }

    stages {
        
        stage('Compile') {
            steps {
             sh 'mvn compile'
            }
        }
        
        stage('Build') {
            steps {
              sh "mvn package"
            }
        }
    }
}
