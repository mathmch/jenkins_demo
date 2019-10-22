pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'Building'
		error("Oops, something went wrong.")
            }
        }
        stage('Test') { 
            steps {
                echo 'Testing' 
            }
        }
        stage('Deploy') { 
            steps {
                echo 'Deploying' 
            }
        }
    }
}