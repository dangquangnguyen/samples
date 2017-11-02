pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        echo 'Hello'
        awsEc2Copy(instanceId: 'abc', vpcId: 'def')
      }
    }
    stage('package') {
      steps {
        echo 'Package'
      }
    }
  }
}