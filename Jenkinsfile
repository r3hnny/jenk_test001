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
                branch 'jnk-br001'
            }
            steps {
                echo 'Hello jnk-br001'
            }            
        }
    }
}
