node('master') 
{
    stage('Continuous Download_slave') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_slave') 
	{
    sh label: '', script: 'mvn package'
	}

    
}
