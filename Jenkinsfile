pipeline {
    agent { label 'linux' }

    stages {
        stage('Run App') {
            steps {
                sh './app.sh'
            }
        }
    }
}
