pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                sh "docker build -t christianscha/pokedex-flask:${env.BUILD_NUMBER} ."
            }
        }
    }
}
