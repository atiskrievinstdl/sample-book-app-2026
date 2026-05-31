pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                build()
            }
        }
        stage('deoloy-dev') {
            steps {
                deploy("dev")
            }
        }
        stage('test-dev') {
            steps {
	    	test("dev")
            }
        }
        stage('deploy-stg') {
            steps {
                deploy("stg")
            }
        }
        stage('test-stg') {
            steps {
	    	test("stg")
            }
        }
        stage('deploy-prd') {
            steps {
                deploy("prd")
            }
        }
        stage('test-prd') {
            steps {
		test("PRD")
            }
        }
    }
}

def build(){
        echo "Building sample-book-app.."
}

def deploy(String environment){
	echo "Deployment to ${environment} environment.."
}

def test(String environment){
	echo "Testing Sample Book App service on ${environment} environment.."
}
