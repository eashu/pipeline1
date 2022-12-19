

pipeline {
	agent any { 
		
		//label 'jenkins1'
	}
  environment {
		//BRANCH_NAME= "Qa"
		
	}
  
  stage ("Pipeline_GIT_CheckOut"){
			//Checkout pipeline code
			steps {
				script {
					sh "echo Stage: pipeline1"
					 {
						git credentialsId: '123456', url: 'https://github.com/eashu/pipeline1.git'
						
					}
				}
			}
		}



