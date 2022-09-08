pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'Echo "Hello Jamari"'
        sh '''
         echo "This is branch2"
         uname -a
         '''
      }
    }
    stage ('Test') {
      steps {
        sh 'echo "Hello Kelly"'
        sh '''
          echo "Testing this out"
          pwd
          '''
      }
    }
  }
}
