pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				 changeset "*WORLD.js", caseSensitive: true
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
