pipeline {
agent any
stages {
	stage('build')
		{
			steps	{
					git rm -r --cached node_modules
					sh 'npm install typescript'
					sh 'npm install cypress@latest --save-dev'              
					sh 'npm run cypress open --spec amazon.spec.ts '
				}
       	}
	}	
}
