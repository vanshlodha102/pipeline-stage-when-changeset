pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				 changeset "**/*.js" 
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
