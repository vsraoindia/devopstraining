pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building using Maven ..'
                sh script:'''
                   #!/bin/bash
                   echo "This is start $(pwd)"
                   cd ./my-app
                   echo "This is my app dir $(pwd)"
                   sh 'mvn package'
                   cd ..
                '''
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

