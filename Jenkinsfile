pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'Echo "Hello World"'
        sh '''
         echo "this will list current dir content from latest"
         ls -lh
         '''
      }
    }
    stage ('Test') {
      steps {
        sh 'echo "Hello Test"'
        sh '''
          echo "This list current dir"
          pwd
          '''
      }
    }
  }
}
