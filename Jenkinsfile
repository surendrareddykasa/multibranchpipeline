node('built-in') 
{
    stage('Continuous Download_Master') 
	{
    git 'https://github.com/surendrareddykasa/jenkins_multibranch15.git'
	}
    stage('Continuous Build_Master') 
	{
    sh label: '', script: 'mvn package'
	} 
	
}
