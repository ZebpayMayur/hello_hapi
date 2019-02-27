#!/usr/bin/env groovy

pipeline {
    agent { docker { image 'node:8.9.3' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
