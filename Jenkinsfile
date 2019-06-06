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
		
		stage ('deploy') {
            steps {
<<<<<<< HEAD
                echo 'eco 'Deployed an artifact'
=======
                mvn 'package'
>>>>>>> 0e642906a8618cb46f359acab619c19d2a96964d
			}
        }
    }
}
    