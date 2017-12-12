#!/usr/bin/env groovy

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'g++ hello.cpp -o hello'
            }
        }
        stage('Test') {
            steps {
                sh './hello'
            }
        }
    }
}
