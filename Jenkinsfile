pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'g++ -o PES1UG20CS437 PES1UG20CS437.cpp'
                build job: 'PES1UG20CS437-1'
            }
        }

        stage('Test') {
            steps {
                sh './PES1UG20CS437
                
            }
        }

        stage('Deploy') {
            steps {
             
            }
        }
    }

    post {
        failure {
            echo 'Pipeline failed!'
        }
    }
}
