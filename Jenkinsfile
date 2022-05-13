pipeline{
   agent any
	parameters {
			choice choices: ['main', 'B1', 'B2'], name: 'branch_name'
	}
	stages{
	   when{
	      branch 'master'
	   }
		stage("One"){
			steps{
				echo "This Job Parameters Value is ${params.branch_name}"
			}
		}
	}
}
