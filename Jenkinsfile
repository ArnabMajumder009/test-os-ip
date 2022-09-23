// test-os-ip

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'uname -r'
               sh 'dnf -y install /path/to/package.rpm'
                sh 'systemctl start docker'
            }
        }
    }
}
