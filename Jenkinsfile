pipeline {
    agent any
    
    tools {
        maven 'Maven 3.8.6'
    }
    stages {
        stage ('Compile Stage') {
            steps {
                    sh 'mvn clean compile'
            }       
        }
        stage ('Testing Stage') {
            steps {
                    sh 'mvn test'
            }   
        }
        stage ('Install Stage') {
            steps {   
                    sh 'mvn install'
            }   
        }		
    }
}
