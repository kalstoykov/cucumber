pipeline {
    agent any
    stages {

        stage('testing pipeline') {
           steps {
		echo 'test pipeline'
                sh 'mkdir from-jenkins'
                sh 'touch from-jenkins/test.txt'
           }
        }
    }
}
