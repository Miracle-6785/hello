pipeline {
    agent any
    
    stages {
        stage('Test ls and pwd') {
            steps {
                script {
                    // Run `pwd` to print the current working directory
                    sh 'pwd'
                    sh 'whoami'
                    // Run `ls` to list files in the current directory
                    sh 'ls -al'
                }
            }
        }
    }
}
