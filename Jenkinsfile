 pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'build'
                 
            }
            post {
                success {
                    echo 'Now Archiving'
                }
            }
        }
    }
}
