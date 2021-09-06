pipeline {
agent any
stages {
	stage('build')
		{
			steps	{
					sh 'npm install typescript'
					sh 'npm install cypress@latest --save-dev'              
					sh 'npm run cypress open --spec amazon.spec.ts '
				}
       	}
	}	
}
