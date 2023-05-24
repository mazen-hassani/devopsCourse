pipeline {
    agent any
    
    tools {
        go 'go-1.20.4'
    }
    
    stages {
        stage('Build') {
            steps {
                sh 'go version'
                sh 'go build main.go'
            }
        }
    }
}
