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
		
		stage ('deploy') {
            steps {
<<<<<<< HEAD
                echo 'eco 'Deployed an artifact'
=======
                mvn 'package'
<<<<<<< HEAD
>>>>>>> 0e642906a8618cb46f359acab619c19d2a96964d
=======
                echo "package completed"
>>>>>>> e8921e09d76f0a80d5ff6ceec83c7bd99f6c1450
			}
        }
    }
}
    