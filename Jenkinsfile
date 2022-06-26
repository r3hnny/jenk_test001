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
                branch 'jnktest-02'
            }
            steps {
                echo 'Hello jnktest-02'
            }            
        }
    }
}
