pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh "npm install -g pnpm"
                sh "pnpm install"
                sh "pnpm build"
                sh "pnpm test"
            }
        }
    }
}