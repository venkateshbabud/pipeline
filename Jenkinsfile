node('master') 
{
    stage('Continuous Download-loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build-loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
