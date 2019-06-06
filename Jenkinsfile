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
<<<<<<< HEAD
                build 'mvn package'
=======
<<<<<<< HEAD
                echo 'eco 'Deployed an artifact'
=======
                mvn 'package'
<<<<<<< HEAD
>>>>>>> 0e642906a8618cb46f359acab619c19d2a96964d
=======
>>>>>>> 43e6c3f93e4c10b358a856a633c1d30f452b1e15
                echo "package completed"
>>>>>>> e8921e09d76f0a80d5ff6ceec83c7bd99f6c1450
			}
        }
    }
}
    