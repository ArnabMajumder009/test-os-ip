// test-os-ip

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'uname -r'
                sh 'docker --version'
                sh 'docker ps -a'
                sh 'docker run -p 80:5000 https://github.com/ArnabMajumder009/test-os-ip.git'
                sh 'helm --version'
             //  sh 'yum install docker-ce docker-ce-cli containerd.io docker-compose-plugin'
               // sh 'systemctl start docker'
            }
        }
    }
}
