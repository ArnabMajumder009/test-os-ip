// test-os-ip

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'curl -s -I https://jenkins-jpe1.r-local.net| grep Server'
            }
        }
    }
}
