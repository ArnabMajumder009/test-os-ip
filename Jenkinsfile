// test-os-ip

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'uname -r'
                cat '/etc/*release*'
            }
        }
    }
}
