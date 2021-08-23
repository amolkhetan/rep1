node('master') 
{
    stage('Continuous Download_M')
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_m') 
	{
    sh label: '', script: 'mvn package'
	}
}
