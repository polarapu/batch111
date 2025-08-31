pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                build quietPeriod: 5, job: 'Job1'
            }
        }
        stage('Test') {
            steps {
                echo 'DevOps World'
                build quietPeriod: 5, job: 'Job2'
            }
        }
    }
}
