pipeline {
  agent any
  stages {
    stage('VPLEX_CODE_CHECK_OUT') {
      steps {
        build 'VPLEX_CODE_CHECK_OUT'
      }
    }
    stage('VPLEX_CODE_BUILD') {
      steps {
        build 'VPLEX_CODE_BUILD'
      }
    }
    stage('VPLEX_ACTION_CREATION') {
      steps {
        build 'VPLEX_ACTION_CREATION'
      }
    }
  }
}