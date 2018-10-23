pipeline {
  agent any
  stages {
    stage('CodeBuild') {
      steps {
        build 'VPLEX_CODE_CHECK_OUT'
      }
    }
    stage('error') {
      steps {
        echo 'Completed'
      }
    }
  }
}