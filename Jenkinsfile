node('master') 
{
    stage('Continuous Download_l') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_l') 
	{
    sh label: '', script: 'mvn package'
	}
}
