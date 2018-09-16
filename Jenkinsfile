pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                   sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
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
