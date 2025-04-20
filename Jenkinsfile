pipeline {
    agent { node { label 'Agen-mahesh'}}

    stages {

        stage('Build') {
            steps {
                echo '🔧 Building the application...'
                // Example: Compile code or install dependencies
                
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running tests...'
                // Example: Run test scripts or tools like pytest, JUnit, etc.
                
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying the application...'
                // Example: SCP files, run a deploy script, use Docker, etc.
                
            }
        }
    }

    post {
        always {
            echo '✅ Pipeline finished.'
        }
        success {
            echo '🎉 Pipeline succeeded!'
        }
        failure {
            echo '❌ Pipeline failed. Check logs!'
        }
    }
}
