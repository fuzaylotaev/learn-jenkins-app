pipeline {
    agent any

    stages {
        stage('without docker') {
            steps {
                sh '''
                    echo "Without docker"
                    ls  -la
                    touch container-no.txt
                '''
            }
        }
    }
}
