pipeline {
    agent any

    stages {
        stage("clone code") {
            steps {
                script {
                    // Let's clone the source
                    git '//github.com/shilpabalegar/amazon.git';
                }
            }
        }

        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
