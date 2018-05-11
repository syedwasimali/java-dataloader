pipeline {
  agent any

  stages {
    stage ('Compiling Stage') {

      steps {
        sh "./gradlew --no-daemon clean build -x test"
      }
    }
  }
}