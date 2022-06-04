pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...!'
            }
        }
        stage('Test') {
            steps {
                build 'demo1'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
    post {
        always {
            echo "pipeline job done!!!!!!!"
        }
    }
}
