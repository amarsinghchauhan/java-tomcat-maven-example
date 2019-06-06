pipeline {
    agent any
    stages {
		stage ('Build Servlet Project') {
            steps {
				bat 'mvn'
				bat 'package'
                echo 'Initializing MVN clean package'
            }
        }
         	 
    }
} 