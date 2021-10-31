pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeset "*.js",
				caseSensitive: true
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
