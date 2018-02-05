Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'php' }
    stages {
        stage('build') {
            steps {
                sh 'docker-compose up -d'
            }
        }
    }
}