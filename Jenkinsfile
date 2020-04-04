pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				 changeset pattern: "helloworld.js", comparator: "GLOB", caseSensitive: true
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
