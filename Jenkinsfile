pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                sh "touch testFile.txt"
                sh "ls"
            }
        }
        stage('Test'){
            steps {
                sh "pwd"
                sh "echo 'Test' > testFile.txt"
            }
        }
        stage('Deploy'){
            steps {
//                 sh "git add testFile.txt"
//                 sh "git commit -m 'added testFile to repo'"
//                 sh "git push"
//need to add code to join onto main branch
                
                sh "cat testFile.txt"
            }
        }
    }
}
