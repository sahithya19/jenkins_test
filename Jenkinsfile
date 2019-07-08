pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo Building theeeee ${BRANCH_NAME}...'
      }
    }
    stage('deploy') {
      steps {
        py add.py
      }
    }
  }
}
