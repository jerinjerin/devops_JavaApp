pipeline {
  agent none {
    stages {
      stage('Git Checkout') {
        steps {
            git url: 'https://github.com/jerinjerin/devops_JavaApp.git', branch: 'master'
        }
      }
    }
  }
}
