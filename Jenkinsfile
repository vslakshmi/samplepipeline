pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                   sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
          docker build -t Hello .
           docker images
                '''
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
