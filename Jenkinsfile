pipeline {
    agent any
    stages {
        stage ('Initialize') {
            steps {
                echo "Initializing code file"
            }
        }
         stage ('clean') {
            steps {
                build 'mvn clean'
                echo "clean completed"
            }
		}
		
		stage ('deploy') {
            steps {
                build 'mvn package'
                echo "package completed"
			}
        }
    }
}
    