pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        checkout scm
      }
    }
    stage('Stage 2') {
      steps {
        echo "Build Release"
        sleep 3
      }
    }
    stage('Stage 3') {
      steps {
        echo "Promote to Environments"
        echo "PR 2"
        sleep 3
      }
    }
  }
}
