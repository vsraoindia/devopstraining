pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building using Maven ..'
                sh 'mvn package'
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

