pipeline {
    agent {
        label 'docloud'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Running on DigitalOcean!'
                sh 'uname -a'
            }
        }
    }
}
