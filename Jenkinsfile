node('master') 
{
    stage('Continuous Download_sl') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_sl') 
	{
    sh label: '', script: 'mvn package'
	}
}

