pipeline {
    agent {
        docker { image 'python' }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		sh 'python3 hellojenkins.py'
            }
        }
    }
}
