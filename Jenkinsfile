pipeline {
    agent any
    stages {

        stage('testing pipeline') {
           steps {
		echo 'test pipeline'
                bat 'mkdir from-jenkins'
                bat 'touch from-jenkins/test.txt'
           }
        }
    }
}
