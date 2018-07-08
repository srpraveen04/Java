pipeline {
    agent { docker { image 'maven:3.3.3' } }
    environment {
    PATH = "C:\\Program Files\\Git\\usr\\bin;C:\\Program Files\\Git\\bin;${env.PATH}"    
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
    }
}
