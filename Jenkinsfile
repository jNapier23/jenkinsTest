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
                sh "cat testFile.txt"
            }
        }
        stage('Deploy'){
            steps {
                sh "git add testFile.txt"
                sh "git commit -m"
                sh "git push"
            }
        }
    }
}
