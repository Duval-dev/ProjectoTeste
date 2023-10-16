pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'hello'
          }
        }

        stage('teste') {
          steps {
            echo 'hello world'
          }
        }

      }
    }

  }
}