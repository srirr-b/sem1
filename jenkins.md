pipeline {
    agent any

    stages {
        stage('Hello World') {
            steps {
                script {
                    // Simple "Hello, World!" message
                    echo 'Hello, World!'
                }
            }
        }
    }
}
