node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/LeonhardtFR/projet_devops.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}