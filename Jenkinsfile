pipeline {
    agent any
    tools { 
      	jdk "JDK11"
	maven "Maven Auto"
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
