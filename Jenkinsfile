pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                git branch: ‘main’, url: 'https://github.com/jesal1234/first.git'
            }
        }

    stages {
        stage('bulding ') {
            steps {
                echo 'Building '
            }
        }
        stage('Testing  ') {
            steps {
                echo 'Testing '
            }
        }
        stage('Deploying') {
            steps {
                echo 'Deploying '
            }
        }
    }
}
}
