pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building using Maven ..'
                sh 'cd my-app'
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

