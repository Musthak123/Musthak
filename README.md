pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo "Build is successful from GitHub"
      }
    }
  }
}
