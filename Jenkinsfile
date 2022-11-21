pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            step {
                scripts {
                   git branch: 'main', credentialsId: 'gitcredentials', url: 'https://github.com/NitinMnb/mrdevops.git'
                }
            }
        }
    }
}
