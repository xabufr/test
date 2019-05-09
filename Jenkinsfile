pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        node(label: 'nodejs')
      }
    }
  }
  environment {
    tes = 'test'
  }
}