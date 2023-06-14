pipeline {
    agent any
    tools { 
      	jdk "jdk11"
	maven "maven3"
    }
    stages {
        stage('Cleanup Workspace') {
            steps {
                echo "Cleaned Up Workspace for "
            }
        }


        stage('Code Build and run') {
            steps {
                 bat 'mvn clean install package'
            }
        }
		}   
}
