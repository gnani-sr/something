node('built-in') 
{
    stage('Continuous Download_gnani') 
	{
    git 'https://github.com/yankils/hello-world.git'
	}
    stage('Continuous Build_gnani') 
	{
    sh label: '', script: 'mvn package'
	}
}
