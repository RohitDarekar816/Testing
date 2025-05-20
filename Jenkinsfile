pipeline {
    cloud {
        label 'doagent'
    }
    stages {
        stage('Build') {
            steps {
                script {
                    def build = docker.build("myapp:${env.BUILD_ID}")
                    build.inside {
                        sh 'echo "Building the application..."'
                    }
                }
            }
        }
    }
}