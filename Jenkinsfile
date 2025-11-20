pipeline {    
    agent any 
    tools {
        jdk 'jdk17'
        maven 'maven3'
    }

    stages {   
        stage('Compile') {
            steps {
                bat 'mvn compile'
            }
        }
        
        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
        
        stage('Build') {
            steps {
                bat 'mvn package'
            }
        }
    }
}
