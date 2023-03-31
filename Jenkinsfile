pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        sh ' start B/ ruby IncreaseVersion.rb > Version.txt'
      }
    }
  }
}