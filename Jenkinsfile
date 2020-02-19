pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        choiceParam('Environment', ['test', 'stage', 'prod'], 'Select environment')
        
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
