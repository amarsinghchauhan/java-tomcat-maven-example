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
                echo "clean completed"
            }
		}
		
		stage ('package') {
            steps {
                mvn 'package'
                echo "package completed"
			}
        }
    }
}
    