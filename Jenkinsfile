pipeline {
    agent any
    tools {
  nodejs 'nodejs'
}
    stages {
        stage("Build") {
            steps {
                echo 'Running build automation'
                sh 'npm install'
            }
        }
        stage("Start node"){
            steps{
                sh 'npm start &'
                echo 'Running build automation'
            }
        }
    }
}
