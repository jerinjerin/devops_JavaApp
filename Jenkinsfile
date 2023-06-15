@Library('my shared library')_
pipeline {
   agent any
   stages {
        stage('Checkout') {
            steps {
                scripts{
                    gitCheckout(
                      branch:"master"
                      url:"https://github.com/jerinjerin/devops_JavaApp.git"
                    )
                }
            }
        }
    }
}