pipeline {
  agent any
  stages {
    stage ("code checkout") {
      steps {
        git 'https://github.com/1234shaik/Conversimg.git'
      }
    }

    stage('gradle build') {
          steps {
            bat 'gradle build"
          }
    }
  }
}
