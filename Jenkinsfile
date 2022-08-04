pipeline {	
    agent any	
    options {	
		timestamps()
		overrideIndexTriggers(true)
    }
    stages {	
        stage('Build') {	
            steps {
                echo 'Hello 2'
		echo env.BRANCH_NAME
            }	
        }	
    }	
}	
