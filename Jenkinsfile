pipeline {
    "release_identifier": "release-3.1.0"
    "repositories": [
    {
      "git_url": "https://github.com/gebeyond/operations-service.git",
      "release_method": "tag"
    },
    {
      "git_url": "https://github.com/gebeyond/support-service.git",
      "release_method": "branch"
    }
  ]
  agent any
  stages {
    stage('Build') {
      steps {
        choiceParam('Environment', ['test', 'stage', 'prod'], 'Select environment')
        echo 'Building..'
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
