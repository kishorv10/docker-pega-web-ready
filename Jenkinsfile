pipeline {
  agent any
  stages {
    stage('Setup') {
      steps {
        echo 'Setting up cloud clusters'
        echo ' Init!!!!'
        sleep 4
      }
    }
     stage('Deploy') {
      steps {
        echo ' Deploying charts and building images'
        sleep 4
      }
    }

    stage('Tests') {
      steps {
        echo 'Running Tests!!'
        sleep 4
      }
    }
  }
}
