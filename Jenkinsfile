pipeline {
   agent any
   stages {
        stage('Checkout') {
            steps {
                scripts{
                    gitCheckout(
                      branch: "main"
                      url: "https://github.com/jerinjerin/devops_JavaApp.git"
                    )
                }
            }
        }
    }
}