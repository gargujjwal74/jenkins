pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                 sh '''
                   sudo usermod -aG sudo jenkins
                   chmod +x deploy.sh
                   ./deploy.sh
                    '''
            }
        }
    }

}

