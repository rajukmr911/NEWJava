pipeline {
    agent any
    tools {
        maven 'maven3'
        jdk  'jdk17'
    }
    
    stages {
        stage('take the code') {
            steps {
               git 'https://github.com/NAGAIT7/JavaProjectJenkins.git'
            }
        }
        stage('compile your code') {
            steps {
                sh "mvn compile"
            }
        }
        stage('xansdfddasd') {
            steps {
                sh "mvn test"
            }
        }
         stage('pacddk') {
            steps {
                sh "mvn package"
            }
        }
    } 
} 
