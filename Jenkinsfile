pipeline{
	agent{docker 'maven:3.3.9'}
	stages{
		stage('build'){
			steps{
				sh -c 'mvn --version'
			}
		}
	}
}
