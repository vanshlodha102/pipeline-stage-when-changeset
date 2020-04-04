pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				 changeset pattern: "WORLD.JS", comparator: "GLOB", caseSensitive: true
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
