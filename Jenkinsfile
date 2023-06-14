pipeline {
  agent none {
    stages {
      stage('Git Checkout') {
        steps {
          script {
            git branch: 'master', urlhttps: '//github.com/jerinjerin/devops_JavaApp.git'
          }
        }
      }
    }
  }
}