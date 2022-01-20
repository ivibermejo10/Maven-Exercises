pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Starting building'
        sh 'mvn clean install -Dlicense.skip=true'
        echo 'Building complete'
      }
    }

  }
}