#!/usr/bin/env groovy
pipeline {
    agent any

    stages {
        stage('Hello All') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hello Branch') {
            when {
                branch 'main'
            }
            steps {
                echo 'Hello jnktest-01'
            }            
        }
    }
}
