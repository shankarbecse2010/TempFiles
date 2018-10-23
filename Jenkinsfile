pipeline {
  agent any
  stages {
    stage('CodeBuild') {
      steps {
        build 'StoragePluginDeployment'
      }
    }
    stage('') {
      steps {
        echo 'Completed'
      }
    }
  }
}