pipeline {
    agent any 
    stages {
        stage('__Clean__') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('__Test__') { 
            steps {
                sh "mvn test"
            }
        }
        stage('__Deploy__') { 
            steps {
                sh "mvn package" 
            }
        }
    }
}
