pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'mvn --version', returnStatus: true, returnStdout: true)
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