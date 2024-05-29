node('built-in') 
{
    stage('Continuous Download_cards') 
	{
    git 'https://github.com/tsri010203/mycode.git'
	}
    stage('Continuous Build-cards') 
	{
    sh label: '', script: 'mvn package'
	}
    
