pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        echo 'Hello'
        awsIdentity()
        awsEc2Identity()
      }
    }
    stage('package') {
      steps {
        echo 'Package'
      }
    }
  }
}