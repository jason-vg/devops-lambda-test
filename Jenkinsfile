//Jenkinsfile (Declarative Pipeline)

pipeline {
    agent { docker { image 'optinetdevops/tfr2:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'python Start.py'
            }
        }
    }
}

