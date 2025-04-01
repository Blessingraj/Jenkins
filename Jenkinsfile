pipeline {
  agent any

  stages {
    stage('Compile') {
      steps {
        echo 'Pipeline started for HTML!'
        bat 'start index.html'  //Windows
        // OR
        // sh 'xdg-open index.html'  //linux
      }
    }
  }
}
