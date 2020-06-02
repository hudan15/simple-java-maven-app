pipeline {
  agent any
  stages {
    stage('pull code') {
      steps {
        git(url: 'https://github.com/hudan15/simple-java-maven-app', branch: 'master', credentialsId: 'ab4ee53a-eff9-454b-ad18-a3a965f5e3ad')
      }
    }

  }
}