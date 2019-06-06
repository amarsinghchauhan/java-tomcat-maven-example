pipeline {
    agent any
    stages {
        stage ('Build servlet Project') {
            steps {
                bat 'mvn clean package'
            }

            post ('Commented') {
                success{
                    echo "Now Archiving..."
                    archiveArtifacts artifacts : '**/*.war'
                }   
            }
        }	
    }
}
    