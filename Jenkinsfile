pipeline {
  agent any
  stages {
    stage('Git Checkout') {
      parallel {
        stage('Git Checkout') {
          steps {
            git(url: 'https://github.com/kennymath/spring-petclinic-new.git', branch: 'main')
          }
        }

        stage('') {
          steps {
            sh 'maven --version'
          }
        }

      }
    }

  }
}