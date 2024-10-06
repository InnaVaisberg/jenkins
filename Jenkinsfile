pipeline {
    agent any 
    stages {
        stage('create NewFolder') {
            steps {
                sh 'mkdir NewFolder' 
            }
        }
        stage('show all folders') {
            steps {
                sh 'ls' 
            }
        }
        stage('get into folder NewFolder') {
            steps {
                sh 'cd NewFolder' 
            }
        }
        stage('create file') {
            steps {
                sh 'touch thisismyscript.py' 
            }
        }        
        stage('show created file') {
            steps {
                sh 'ls' 
            }
        }
    }
}