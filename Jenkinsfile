pipeline{
   agent any
	parameters {
			choice choices: ['master', 'cr101', 'rel-1'], name: 'branch_name'
	}
	stages{
		stage("One"){
			steps{
				echo "This Job Parameters Value is ${params.branch_name}"
			}
		}
	}
}
