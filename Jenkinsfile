pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Building sample-book-app.."
            }
        }
        stage('deoloy-dev') {
            steps {
                echo "Deployment to DEV environment.."
            }
        }
        stage('test-dev') {
            steps {
                echo "Testing Sample Book App service on DEV environment..."
            }
        }
        stage('deploy-stg') {
            steps {
                echo "Deployment to STG environment.."
            }
        }
        stage('test-stg') {
            steps {
                echo "Testing Sample Book App service on STG environment..."
            }
        }
        stage('deploy-prd') {
            steps {
                echo "Deployment to PRD environment.."
            }
        }
        stage('test-prd') {
            steps {
                echo "Testing Sample Book App service on STG environment..."
            }
        }
    }
}
