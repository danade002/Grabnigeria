pipeline {
    agent any 
    stages {
        stage('__Clean__') { 
            steps {
                bat "mvn clean"
            }
        }
        stage('__Test__') { 
            steps {
                bat "mvn test"
            }
        }
        stage('__Deploy__') { 
            steps {
                bat "mvn package" 
            }
        }
    }
}
