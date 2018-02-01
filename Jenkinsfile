
pipeline {

    agent any

    stages {
        stage('Build') {
            steps {
                sh 'set path=%path%:C:\appserv\apache-maven-3.5.2-bin\apache-maven-3.5.2\bin'
                sh 'mvn clean package'
            }
        }
    }
}