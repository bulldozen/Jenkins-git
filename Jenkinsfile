pipeline {
    agent any
    environment {
        AWS_SECRET = credentials('Secrettxt')
        }        

    stages {
        stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
                echo "The encrypted password is ${AWS_SECRET}"
            }
        }
    }
}
