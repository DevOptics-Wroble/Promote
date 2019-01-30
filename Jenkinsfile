// Jenkinsfile scripted pipeline
	node {
	    stage ('checkout') {
	        checkout scm
	    }
	    stage ('produce') {
	        // Notify DevOptics that this run produced plugin-a.txt.
	        gateConsumesArtifact file: 'plugin-0130.txt'
	          sh 'sleep 30'
	    }      
	}
