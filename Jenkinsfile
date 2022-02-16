node('master') 
{
    stage('Continuous Download master') 
	{
    git 'https://github.com/gamedoper/maven.git'
	}
    stage('Continuous Build master') 
	{
    sh label: '', script: 'mvn package'
	}
   
}

