node('master') 
{
    stage('Continuous Download-master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build-master') 
	{
    sh label: '', script: 'mvn package'
	}
}
}
