pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                nodejs(nodejs: 'Node 12.x') 
                    sh 'npm config ls'
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
