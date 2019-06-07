pipeline {
    agent any
    stages {
        stage ('Build servlet Project') {
            steps {
                bat 'mvn clean package'
            }

            post {
                success{
                    echo "Now Archiving..."
                    archiveArtifacts artifacts : '**/*.war'
                }   
            }
        }	
    }
}
    