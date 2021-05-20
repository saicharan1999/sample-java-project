pipeline{
    agent any 
	stages{
	    stage("hello") {
		    steps{
		     echo "Hello World!"
			 }
	    }
		    
		    stage("Git clone") {
			    steps{
				    git url:'https://github.com/saicharan1999/sample-java-project.git'
			    }
		    }
			 
	}
}	
