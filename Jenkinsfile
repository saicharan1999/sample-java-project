pipeline{
    agent any 
	stages{
	    stage("hello") {
		    steps{
		     echo "Hello World!"
			 }
	    }
		    
		    stage("build") {
			    steps{
				    sh "mvn clean install"
			    }
		    }
			 
	}
}	
