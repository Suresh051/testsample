pipeline {
  agent any
  stages {
  stage('Cleanup') {
    cleanWs()  
  }
  stage('Stage 1') {
      steps {
        script {
          echo 'Stage 1'
        }
      }
    }
  stage('Stage 2') {
      steps {
        script {
          echo 'Stage 2'
        }
      }
    }
  }
}
