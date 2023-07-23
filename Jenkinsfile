@Library(build-api-shared-lib@main)

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                println "Inside build package..."                
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
