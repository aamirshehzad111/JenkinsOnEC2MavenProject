pipeline {
  agent any
  stages {
      stage('Maven') {
        steps {
            sh "mvn --settings settings.xml clean deploy -e"
        }
      }
  }
}
