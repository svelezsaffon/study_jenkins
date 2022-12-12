pipeline {
    agent any

    stages {
        stage('show_dir') {
            steps {
                ls
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
    }
}