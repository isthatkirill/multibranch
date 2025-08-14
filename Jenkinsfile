pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'THIRD'
                sh 'ls -la'
                sleep 300
                echo "This is MAIN branch"
            }
        }
    }
}
