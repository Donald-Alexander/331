pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        sh 'ruby IncreaseVersion.rb Version.txt'
      }
    }
  }
}