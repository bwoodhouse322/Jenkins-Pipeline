pipeline {
    agent any
    stages{
        stage ('Build'){
            steps{
                checkout scm
            }
        }

        stage ('Check for Versions') {
            steps{
                sh "javac --version"
            }
        }   
    }
}