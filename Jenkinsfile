pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build 'CM_INN_JOB1'
      }
    }

    stage('Deploy') {
      steps {
        bat(script: 'java -version', returnStatus: true, returnStdout: true)
      }
    }

    stage('Test') {
      steps {
        bat(script: 'echo "Testing started and completed"', returnStatus: true, returnStdout: true)
      }
    }

  }
}