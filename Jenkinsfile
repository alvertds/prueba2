pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                sh "docker build -t alvertds/pokedex-flask:${env.BUILD_NUMBER} ."
            }
        }
    }
}
