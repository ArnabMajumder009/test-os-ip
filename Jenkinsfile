// test-os-ip

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'uname -r'
                sh 'docker --version'
                sh 'docker ps -a'
             //  sh 'yum install docker-ce docker-ce-cli containerd.io docker-compose-plugin'
               // sh 'systemctl start docker'
            }
        }
    }
}
