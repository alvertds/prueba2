pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                sh "docker build -t zdenkoo98/pokedex-flask:${env.BUILD_NUMBER} ."
            }
        }
    }
}
