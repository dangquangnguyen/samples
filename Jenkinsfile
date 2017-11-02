pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        echo 'Hello'
        awsIdentity()
      }
    }
    stage('package') {
      steps {
        echo 'Package'
      }
    }
  }
}