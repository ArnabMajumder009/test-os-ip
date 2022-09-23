// test-os-ip

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'uname -r'
               sh 'dnf install docker-ce docker-ce-cli containerd.io docker-compose-plugin'
                sh 'systemctl start docker'
            }
        }
    }
}
