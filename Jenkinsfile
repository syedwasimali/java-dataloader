pipeline {
  agent any

  stages {
    stage ('Compiling Stage') {

      steps {
        sh "gradle --no-daemon clean build -x test"
      }
    }
  }
}