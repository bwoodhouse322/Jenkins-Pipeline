pipeline {
    agent any
    stages{
        stage ('Build'){
            checkout scm
        }

        stage ('Check for Versions') {
            sh "javac --version"
        }   
    }
}