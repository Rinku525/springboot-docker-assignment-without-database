pipeline{
    tools {
        maven 'maven-3.8.1'
        }
    agent any
    stages{
        stage('git code'){
            steps{
                git branch: 'main', url: 'https://github.com/Rinku525/springboot-docker-assignment-without-database.git'
            }
        }
        stage('build project'){
            steps{
                 sh 'mvn clean package'
            }
        }
    }
