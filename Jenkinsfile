Jenkinsfile (Declarative Pipeline)

pipeline {
    agent { docker 'git version 1.7.9.5' }
    stages {
        stage('build') {
            steps {
                sh 'git --version'
            }
        }
    }
}
