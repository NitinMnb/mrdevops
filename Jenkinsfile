pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
                  git branch: 'main', credentialsId: 'gitcredentials', url: 'https://github.com/NitinMnb/mrdevops.git'
               
            }
        }
    }
}
