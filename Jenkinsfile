pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
          script {
                git rev-parse --verify "test-branch"
          }
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}
