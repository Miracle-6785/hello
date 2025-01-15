pipeline {
    agent any
    
    stages {
        stage('Test ls and pwd') {
            steps {
                script {
                    // Run `pwd` to print the current working directory
                    sh 'pwd'
                    sh 'whoami'
                    sh 'echo 17:28'
                    // Run `ls` to list files in the current directory
                    sh 'ls -al'
                }
            }
        }
    }
}
