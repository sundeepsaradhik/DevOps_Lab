pipeline {
 agent any
 stages{
  stage("Build_stage"){
	steps{
	    echo "Building Project....."
	}
  }
  stage("Test_stage"){
    	steps{
	    echo "Testing Project...."
	}
  }
  stage("Deploy_stage"){
	steps{
	    echo "Deploying Project...."
	}
  }
 }
 post{
   always{
    echo "Thank You"
    }
  }
} 
