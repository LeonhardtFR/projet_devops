pipeline {
    agent any
    stages {
        stage('clone') {
            steps {
            sh "rm -rf *"
            sh "git clone https://github.com/LeonhardtFR/projet_devops.git"
            }
        }
        stage('build') {
            steps {
            sh "cd projet_devops/ && javac Main.java"
            }
        }
        stage('run') {
            steps {
            sh "cd projet_devops/ && java Main"
            }
        }
    }
}