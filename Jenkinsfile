pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                echo 'Running build automation'
                sh 'npm install'
            }
        }
        stage("Start node"){
            steps{
                sh 'nohup npm start &'
            }
        }
    }
}
