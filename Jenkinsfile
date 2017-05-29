pipeline {
  agent none
  stages {
    stage('Printing') {
      steps {
        echo 'Halooo'
      }
    }
    stage('error') {
      steps {
        input(message: 'Do you want to deploy to live?', id: 'deploy')
      }
    }
  }
}