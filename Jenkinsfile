pipeline {
  agent any 
  
  stages {
    stage ('cleaning laanc-ap-client .m2 directory') {
      steps {
        script {
          sh "printenv"
          sh "rm -rf $HOME/testdir"
        }
      }
    }
  }
}
