pipeline {
  agent any
  stages {
  
  stage('Stage 1') {
      when { { branch 'master'; branch 'release/**' } }
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
  post {
    always {
      echo 'I will always execute this!'
      cleanWs()
    }
  }
}
