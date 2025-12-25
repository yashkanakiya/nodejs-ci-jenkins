pipeline {
    agent any

    tools {
        nodejs 'nodejs-18' 
    }

    stages {
        stage('Checkout Code') {
            steps {
                // git 'https://github.com/yashkanakiya/nodejs-ci-jenkins.git'
                checkout scm
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run Tests') {
            steps {
                sh 'npm test'
            }
        }
    }
}
