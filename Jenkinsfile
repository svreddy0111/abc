pipeline{
   agent any
	parameters {
			choice choices: ['main', 'B1', 'B2'], name: 'branch_name'
	}
	stages{
	   
		stage("One"){
		when{
	      branch 'master'
	   }	 
			steps{
				echo "This Job Parameters Value is ${params.branch_name}"
			}
		}
	}
}
