node('master') 
{
    stage('CD-S1-GIt') 
	{
      git 'https://github.com/BABJI-AWS-DEVOPS/WARFILE-43-44-10am.git'
    }
}

node('master') 
{
   stage('S2-CB') 
   {
    sh 'mvn package'
   }
}
