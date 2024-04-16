pipeline{
	agent any
	stages{
		stage ('cleaning stage'){
			steps{
				bat "mvn clean"
			}
	}
		stage ('testing stage'){
			steps{
				bat "mvn test"
			}
	}
		stage ('packing stage'){
			steps{
				bat "mvn package"
			}
	}
}
}
	
