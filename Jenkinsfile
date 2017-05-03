pipeline {
  agent none
  stages {
    stage('Printing') {
      steps {
        echo 'Halooo'
      }
    }
    stage('') {
      steps {
        cleanWs()
        input(message: 'Do you want to deploy to live?', id: 'deploy')
      }
    }
  }
}