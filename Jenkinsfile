node('master') 
{
    stage('Continuous Download_master') 
	{
    git 'https://github.com/abhinavthula/sampleproject.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
}
