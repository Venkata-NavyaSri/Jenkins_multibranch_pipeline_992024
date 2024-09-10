node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/Venkata-NavyaSri/Jenkins_multibranch_pipeline_992024.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
