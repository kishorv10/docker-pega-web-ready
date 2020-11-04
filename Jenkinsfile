pipeline {
  agent any
  stages {
    stage('Setup') {
      steps {
        echo 'Setting up cloud clusters'
        echo ' Init!!!!'
        sleep 5
      }
    }
     stage('Deploy') {
      steps {
        echo 'hello there!!'
        echo ' In second stage'
        echo ' Deploying charts and building images'
        sleep 5
      }
    }

    stage('Tests') {
      steps {
        echo 'Running Tests!!'
        sleep 5
      }
    }
  }
}
