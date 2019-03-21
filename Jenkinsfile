pipeline {
    agent any
    stages {
        stage('myStage'){
            steps {
                bat 'dir' 
            }
        }
        stage('Build') {
            steps { 
                dir 'dir' 
            }
        }
    }
}
