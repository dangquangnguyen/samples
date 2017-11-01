pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        sh 'echo "Hello World"'
        echo 'Hello'
      }
    }
    stage('package') {
      steps {
        echo 'Package'
      }
    }
    stage('deploy to test') {
      steps {
        parallel(
          "deploy to test": {
            sleep 2
            echo 'Say Hello World'
            
          },
          "deploy to performance test": {
            sleep 20
            
          },
          "deploy to security test": {
            echo 'Deploy to security test'
            
          }
        )
      }
    }
  }
}