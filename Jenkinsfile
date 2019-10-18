pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'Building'
		error("Build failed because of this and that..")
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