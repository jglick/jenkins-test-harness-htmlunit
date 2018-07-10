pipeline {
    agent { label 'linux' }

    stages {
        stage('Build') {
            tools {
                maven 'mvn'
                jdk 'jdk8'
            }
            steps {
                sh 'mvn -B clean install'
            }
        }
    }
}
