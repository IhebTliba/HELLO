 pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'build'
                 
            }
         stage('Test') {
            steps {
                 sh 'mvn -f HELLO/pom.xml test'
                 
            }
         
             
        }
    }
}
