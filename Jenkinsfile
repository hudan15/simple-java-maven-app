pipeline {
  agent any
  stages {
    stage('bulid') {
      parallel {
        stage('bulid') {
          steps {
            echo 'bulid'
          }
        }

        stage('test') {
          steps {
            echo 'test'
          }
        }

        stage('deploy') {
          steps {
            echo 'deploy'
          }
        }

      }
    }

  }
}