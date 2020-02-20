pipeline {
  agent any 
  
  stages {
    stage ('cleaning laanc-ap-client .m2 directory') {
      steps {
        script {
          echo ${JENKINS_HOME}
          sh 'mvn --version'
        }
      }
    }
  }
}
