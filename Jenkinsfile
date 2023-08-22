pipeline{
    agent any
    tools{
        maven 'maven'
    }
    stages{
        stage('Cloning'){
            echo "Welcome to Maven Project"
        }

        stage('cleaning the Repository'){
            sh 'mvn clean'

        }

        stage('Build'){
            sh 'mvn package'

        }
    }
}