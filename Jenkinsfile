pipeline{
   agent any
	parameters {
			choice choices: ['main', 'B1', 'B2'], name: 'branch_name'
	}
	stages{
		stage("One"){
			steps{
				echo "This Job Parameters Value is ${params.branch_name}"
				sh '''
				echo my name is ${branch_name}
				'''
			}
		}
	}
}
