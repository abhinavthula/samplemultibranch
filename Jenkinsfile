node('master') 
{
    stage('Continuous Download_login') 
	{
    git 'https://github.com/abhinavthula/sampleproject.git'
	}
    stage('Continuous Build_login') 
	{
    sh label: '', script: 'mvn package'
	}
}
