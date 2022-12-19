

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
						git credentialsId: '41591095-b555-4d2e-a7dd-876fd6932e54', url: 'https://github.com/eashu/pipeline1.git'
						)
					}
				}
			}
		}



