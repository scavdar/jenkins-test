pipeline {
  agent { docker { image 'python:3.7.2' } }
  stages {
    stage('build') {
      steps {
        echo 'Building..'
        sh 'python test.py'
      }
    }
  }
}
