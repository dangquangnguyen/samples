pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        echo 'Hello'
        awsIdentity()
        awsEc2Identity()
        awsEc2Copy(instanceId: 'instance1', vpcId: 'vpc1')
      }
    }
    stage('package') {
      steps {
        echo 'Package'
      }
    }
  }
}