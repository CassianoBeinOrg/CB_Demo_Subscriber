pipeline {
  agent any
  stages {
    stage('Example') {
      steps {
        echo 'Subscribing to a trigger'
      }
    }
  }
  triggers {
    eventTrigger(jmespathQuery('eventName==\'helloWorld\''))
  }
}