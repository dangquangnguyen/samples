pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        echo 'Hello'
        awsEc2Copy(instanceId: 'abc', vpcId: 'def')
        awsCopyDb(vpcId: 'ABC', dbInstanceId: 'DEF')
      }
    }
    stage('package') {
      steps {
        echo 'Package'
      }
    }
  }
}