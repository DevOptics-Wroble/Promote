// Jenkinsfile scripted pipeline - 1/15/19 
	node {
	    stage ('checkout') {
	        checkout scm
	    }
	    stage ('produce') {
	        // Notify DevOptics that this run produced plugin-a.txt.
	        gateConsumesArtifact file: 'plugin-0240.txt'
	          sh 'sleep 45'
	    }      
	}
