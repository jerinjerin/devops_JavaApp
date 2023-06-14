pipeline {
  agent {
    stages {
      stage('Git Checkout stage ') {
        steps {
          script {
            git branch: 'master', urlhttps: '//github.com/jerinjerin/devops_JavaApp.git'
          }
        }
      }
    }
  }
}