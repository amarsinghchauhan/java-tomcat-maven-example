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
                mvn 'clean'
            }
		}
		
		stage ('package') {
            steps {
                mvn 'package'
			}
        }
    }
}
    