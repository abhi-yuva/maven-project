pipeline{
    agent any
    tools{
        maven 'maven'
    }
    stages{
        stage('Cloning'){
            steps{
                echo "Welcome to Maven Project"

            }
        }

        // stage('cleaning the Repository'){
        //     steps{
        //         sh 'mvn clean'
        //     }
            

        // }

        stage('Build'){
            steps{
                sh 'mvn package'
            }
        }
    }
}