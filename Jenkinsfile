pipeline {
  agent any 
  
  stages {
    stage ('cleaning laanc-ap-client .m2 directory') {
      steps {
        script {
          echo "${env.JENKINS_HOME}"
          sh rm -rf "${env.JENKINS_HOME}"/testdir
        }
      }
    }
  }
}
