pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                  nodejs(nodeJSInstallationName: 'nodejs') {
                    sh 'npm config ls'
                }
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
