pipeline {
    agent {
        label 'doagent'
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
