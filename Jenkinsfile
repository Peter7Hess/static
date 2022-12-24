pipeline {
    agent any
  stages {
    stage('Lint HTML') {
      steps {
          sh 'tidy -q -e index.html'
      }
    }
    stage('Upload to IBMCloud') {
      steps {
          sh 'echo "Hello World with IBMCloud creds"'
      }
    }
  }
}
