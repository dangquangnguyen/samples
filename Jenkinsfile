pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        echo 'Hello'
        awsIdentity()
        awsEc2Identity()
        awsEc2Copy()
      }
    }
    stage('package') {
      steps {
        echo 'Package'
      }
    }
  }
}