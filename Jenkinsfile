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
            echo '✅ Pipeline Completed.'
        }
        success {
            echo '🎉 Pipeline successful!'
        }
        failure {
            echo '❌ Pipeline failed. Check logs!'
        }
    }
}
