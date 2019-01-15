// Jenkinsfile scripted pipeline - 1/11/19 a
	node {
	    stage ('checkout') {
	        checkout scm
	    }
	    stage ('produce') {
	        // Notify DevOptics that this run produced plugin-a.txt.
	        gateConsumesArtifact type: “docker”, id: “789”
	          sh 'sleep 45'
	    }      
	}
