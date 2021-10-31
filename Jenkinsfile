pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeset pattern: "helloworld.js", caseSensitive: true
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
