pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        node(label: 'docker') {
          sh 'mkdir jenkins'
        }
        
      }
    }
  }
}